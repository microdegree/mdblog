---
title: 'CSSBasics'
author: [Ghost]
tags: []
image: img/marvin-meyer-794521-unsplash.jpg
date: '2020-11-02T10:00:00.000Z'
draft: false
---



# CSS Basics

[![Hemalatharao](https://miro.medium.com/fit/c/96/96/0*_LxkLpCb93uoJDAA)](https://medium.com/@hemalatharao936?source=post_page-----846ef27f72c3--------------------------------)

[Hemalatharao](https://medium.com/@hemalatharao936?source=post_page-----846ef27f72c3--------------------------------)

Follow

[Nov 4](https://medium.com/microdegree/css-basics-846ef27f72c3?source=post_page-----846ef27f72c3--------------------------------)  ·  7  min read

ಸಿಎಸ್ಎಸ್(CSS) (Cascading Style Sheet) ವೆಬ್ contentನ್ನು ವಿನ್ಯಾಸಗೊಳಿಸುವ ಕೋಡ್ ಆಗಿದೆ.  _ಸಿಎಸ್ಎಸ್_  _ಬೇಸಿಕ್ಸ್,_  ಕಲಿಯಲು ಬೇಕಾದ ವಿಷಯವನ್ನು ತಿಳಿಸುತ್ತದೆ. ನಾನು textಗಳನ್ನು ಕೆಂಪು ಬಣ್ಣಕ್ಕೆ ಹೇಗೆ ಮಾಡುವುದು? ನನ್ನ ವೆಬ್‌ಪುಟವನ್ನು background colorಗಳು ಮತ್ತು ಬಣ್ಣಗಳಿಂದ ಅಲಂಕರಿಸುವುದು ಹೇಗೆ? ಎನ್ನುವ ಪ್ರಶ್ನೆಗಳಿಗೆ ಉತ್ತರಿಸುತ್ತೇವೆ.

**ಸಿಎಸ್ಎಸ್(CSS) ಎಂದರೇನು?**

HTML ನಂತೆ, ಸಿಎಸ್ಎಸ್ ಪ್ರೋಗ್ರಾಮಿಂಗ್ ಲ್ಯಾಂಗ್ವೇಜ್ ಅಲ್ಲ, ಮಾರ್ಕ್ಅಪ್ ಲ್ಯಾಂಗ್ವೇಜ್ ಅಲ್ಲ.  **ಸಿಎಸ್ಎಸ್**  **ಇದು**  **Style Sheet**  **ಲ್ಯಾಂಗ್ವೇಜ್**. HTML elementಗಳನ್ನು ಆಯ್ದ ಶೈಲಿಯಲ್ಲಿ ಬಳಸಲು ನೀವು ಸಿಎಸ್ಎಸ್ನ್ನು ಬಳಸಲಾಗುತ್ತದೆ. ಉದಾಹರಣೆಗೆ, ಈ ಸಿಎಸ್ಎಸ್ ಪ್ಯಾರಾಗ್ರಾಫ್ ಪದವನ್ನು ಆಯ್ಕೆ ಮಾಡುತ್ತದೆ, ಬಣ್ಣವನ್ನು ಕೆಂಪು ಬಣ್ಣಕ್ಕೆ ಹೊಂದಿಸುತ್ತದೆ:

p {

color: red;

}

text editor ಬಳಸಿ, ಸಿಎಸ್‌ಎಸ್‌ನ ಮೂರು ಸಾಲುಗಳನ್ನು ಹೊಸ ಫೈಲ್‌ಗೆ ಹಾಕಿ.  **styles** ಹೆಸರಿನ ಡೈರೆಕ್ಟರಿಯಲ್ಲಿ ಫೈಲ್ ಅನ್ನು  **style.css**  ಎಂದು save ಮಾಡಿ.

ಕೋಡ್ ಕಾರ್ಯನಿರ್ವಹಿಸಲು, ನಾವು ಇನ್ನೂ ಈ ಸಿಎಸ್ಎಸ್ ಅನ್ನು ನಿಮ್ಮ HTML ಡಾಕ್ಯುಮೆಂಟ್‌ಗೆ attach ಮಾಡಬೇಕಾಗಿದೆ. ಇಲ್ಲದಿದ್ದರೆ, ಸ್ಟೈಲಿಂಗ್ HTML ನ ನೋಟವನ್ನು ಬದಲಾಯಿಸುವುದಿಲ್ಲ. (ನೀವು ನಮ್ಮ ಯೋಜನೆಯನ್ನು ಅನುಸರಿಸದಿದ್ದರೆ, ಫೈಲ್‌ಗಳು ಮತ್ತು HTML ಮೂಲಗಳೊಂದಿಗೆ ವ್ಯವಹರಿಸುವುದನ್ನು ಓದಲು ಇಲ್ಲಿ [Dealing with files](https://developer.mozilla.org/en-US/Learn/Getting_started_with_the_web/Dealing_with_files)  and  [HTML basics](https://developer.mozilla.org/en-US/Learn/Getting_started_with_the_web/HTML_basics)  ನೋಡಿ.

1.  ನಿಮ್ಮ index.html ಫೈಲ್ ತೆರೆಯಿರಿ. ಕೆಳಗಿನ ಸಾಲನ್ನು head ಲ್ಲಿ ಹಾಕಿ (<head> ಮತ್ತು </ head> ಟ್ಯಾಗ್‌ಗಳ ನಡುವೆ):<link href=”styles/style.css” rel=”stylesheet”>
2.  index.html ಅನ್ನು save ಮಾಡಿ ಮತ್ತು ಅದನ್ನು ನಿಮ್ಮ ಬ್ರೌಸರ್‌ನಲ್ಲಿ ಲೋಡ್ ಮಾಡಿ. ನೀವು ಈ ರೀತಿಯದನ್ನು ನೋಡಬೇಕು:

![Image for post](https://miro.medium.com/max/52/0*au9rPD1C5Q4FUliH?q=20)

![Image for post](https://miro.medium.com/max/889/0*au9rPD1C5Q4FUliH)

ನಿಮ್ಮ ಪ್ಯಾರಾಗ್ರಾಫ್ text ಕೆಂಪು ಆಗಿದ್ದರೆ, ಅಭಿನಂದನೆಗಳು! ನಿಮ್ಮ ಸಿಎಸ್ಎಸ್ ಕಾರ್ಯನಿರ್ವಹಿಸುತ್ತಿದೆ.

**ಸಿಎಸ್ಎಸ್**  **ರೂಲ್**  **ಸೆಟ್‌ನ Anatomy(Anatomy of CSS ruleset)**

ಅದು ಹೇಗೆ ಕಾರ್ಯನಿರ್ವಹಿಸುತ್ತದೆ ಎಂಬುದನ್ನು ಅರ್ಥಮಾಡಿಕೊಳ್ಳಲು ಕೆಂಪು ಪ್ಯಾರಾಗ್ರಾಫ್ textಗಾಗಿ ಸಿಎಸ್ಎಸ್ ಕೋಡ್ ಅನ್ನು ವಿಂಗಡಿಸೋಣ:

![Image for post](https://miro.medium.com/max/60/0*y1tL3-fY9VpIrSI9?q=20)

![Image for post](https://miro.medium.com/max/1000/0*y1tL3-fY9VpIrSI9)

ಇಡೀ ರಚನೆಯನ್ನು  **ರೂಲ್‌ಸೆಟ್**  ಎಂದು ಕರೆಯಲಾಗುತ್ತದೆ. (ರೂಲ್‌ಸೆಟ್ ಎಂಬ ಪದವನ್ನು ಸಾಮಾನ್ಯವಾಗಿ ನಿಯಮ ಎಂದು ಕರೆಯಲಾಗುತ್ತದೆ.) ಪ್ರತ್ಯೇಕ ಭಾಗಗಳ ಹೆಸರುಗಳನ್ನು ಗಮನಿಸಿ:

**ಸೆಲೆಕ್ಟರ್(Selector)**

ರೂಲ್‌ಸೆಟ್‌ನ ಪ್ರಾರಂಭದಲ್ಲಿ ಇದು HTML elementನ ಹೆಸರು. ಇದು ಸ್ಟೈಲ್ ಮಾಡಬೇಕಾದ element (ಗಳನ್ನು) ಅನ್ನು define ಮಾಡುತ್ತದೆ (ಈ ಉದಾಹರಣೆಯಲ್ಲಿ, <p> elementಗಳು). ಬೇರೆ elementನ್ನು ವಿನ್ಯಾಸಗೊಳಿಸಲು, ಸೆಲೆಕ್ಟರ್ ಅನ್ನು ಬದಲಾಯಿಸಿ.

**Declaration**

ಇದು ಬಣ್ಣದಂತಹ ಒಂದೇ color: red; ನೀವು ಸ್ಟೈಲ್ ಮಾಡಲು ಬಯಸುವ elementನ propertiesಗಳನ್ನು ಇದು ನಿರ್ದಿಷ್ಟಪಡಿಸುತ್ತದೆ.

**Properties**

ಇದು HTML elements ನ್ನು ಸ್ಟೈಲ್ ಮಾಡುತ್ತದೆ. (ಈ ಉದಾಹರಣೆಯಲ್ಲಿ, ಬಣ್ಣವು <p> elementಗಳ propertyಯಾಗಿದೆ.) ಸಿಎಸ್ಎಸ್ನಲ್ಲಿ, ನಿಯಮದಲ್ಲಿ ಯಾವ propertyಯನ್ನು ಸ್ಟೈಲ್ ಮಾಡಬೇಕೆಂದು ನೀವು ಆರಿಸುತ್ತೀರಿ.

**Property value**

propertyಯ ಬಲಭಾಗದಲ್ಲಿ-colon(:) ನಂತರ-**property-value** ಇದೆ. ನಿರ್ದಿಷ್ಟ propertyಗಾಗಿ many possible appearances ಒಂದನ್ನು ಇದು ಆಯ್ಕೆ ಮಾಡುತ್ತದೆ. (ಉದಾಹರಣೆಗೆ, ಕೆಂಪು ಬಣ್ಣಕ್ಕೆ ಹೆಚ್ಚುವರಿಯಾಗಿ ಅನೇಕ ಬಣ್ಣ valueಗಳಿವೆ.)

ಸಿಂಟ್ಯಾಕ್ಸ್ನ(Syntax) ಇತರ ಪ್ರಮುಖ ಭಾಗಗಳನ್ನು ಗಮನಿಸಿ:

-   ಸೆಲೆಕ್ಟರ್ ಹೊರತುಪಡಿಸಿ, ಪ್ರತಿ ರೂಲ್ ಸೆಟ್ ಅನ್ನು ಸುರುಳಿಯಾಕಾರದ ಕಟ್ಟುಪಟ್ಟಿಗಳಲ್ಲಿ ಸುತ್ತಿಡಬೇಕು. ({})
-   ಪ್ರತಿ declaration ಒಳಗೆ, propertyಯನ್ನು ಅದರ value ಅಥವಾ valuesಗಳಿಂದ ಬೇರ್ಪಡಿಸಲು ನೀವು colon (:) ಅನ್ನು ಬಳಸಬೇಕು.
-   ಪ್ರತಿ ರೂಲ್‌ಸೆಟ್‌ನಲ್ಲಿ, ಪ್ರತಿ declarationನ್ನು ಮುಂದಿನದರಿಂದ ಬೇರ್ಪಡಿಸಲು ನೀವು semicolon ಚಿಹ್ನೆಯನ್ನು (;) ಬಳಸಬೇಕು.

ಒಂದು ರೂಲ್‌ಸೆಟ್‌ನಲ್ಲಿ ಬಹು property valuesಗಳನ್ನು ಮಾರ್ಪಡಿಸಲು, ಅವುಗಳನ್ನು ಈ ರೀತಿಯಾಗಿ semicolon ಚಿಹ್ನೆಗಳಿಂದ ಬೇರ್ಪಡಿಸಿ ಬರೆಯಿರಿ:

p {

color: red;

width: 500px;

border: 1px solid black;

}

**ಬಹು**  **elementsಗಳನ್ನು**  **ಆಯ್ಕೆ**  **ಮಾಡಲಾಗುತ್ತಿದೆ(selecting multiple elements)**

ನೀವು ಅನೇಕ elementsಗಳನ್ನು ಆಯ್ಕೆ ಮಾಡಬಹುದು ಮತ್ತು ಅವೆಲ್ಲಕ್ಕೂ ಒಂದೇ ರೂಲ್‌ಸೆಟ್ ಅನ್ನು ಅನ್ವಯಿಸಬಹುದು. ಬಹು selectorರನ್ನು semicolonದಿಂದ ಪ್ರತ್ಯೇಕಿಸಿ. ಉದಾಹರಣೆಗೆ:

p, li, h1 {

color: red;

}

**ವಿವಿಧ**  **ರೀತಿಯ**  **ಆಯ್ಕೆದಾರರು(different types of selectors)**

ವಿವಿಧ ರೀತಿಯ selectors ಇದ್ದಾರೆ. ಮೇಲಿನ ಉದಾಹರಣೆಗಳು  **ಎಲಿಮೆಂಟ್**  **ಸೆಲೆಕ್ಟರ್‌ಗಳನ್ನು**  ಬಳಸುತ್ತವೆ, ಅದು ನಿರ್ದಿಷ್ಟ ಪ್ರಕಾರದ ಎಲ್ಲಾ elementsಗಳನ್ನು ಆಯ್ಕೆ ಮಾಡುತ್ತದೆ. ಆದರೆ ನಾವು ಹೆಚ್ಚು ನಿರ್ದಿಷ್ಟವಾದ ಆಯ್ಕೆಗಳನ್ನು ಮಾಡಬಹುದು. ಕೆಲವು ಸಾಮಾನ್ಯ ವಿಧದ selectors ಇಲ್ಲಿವೆ:

![Image for post](https://miro.medium.com/max/60/0*YN6IWMrHfv-tFTjj?q=20)

![Image for post](https://miro.medium.com/max/1000/0*YN6IWMrHfv-tFTjj)

ಕಂಡುಹಿಡಿಯಲು ಇನ್ನೂ ಅನೇಕ selectors ಇದ್ದಾರೆ. ಇನ್ನಷ್ಟು ತಿಳಿದುಕೊಳ್ಳಲು, ಎಂಡಿಎನ್  [Selectors guide](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Getting_started/Selectors)  ನೋಡಿ.

**ಫಾಂಟ್‌ಗಳು**  **ಮತ್ತು**  **ಪದ(Fonts and text)**

ಈಗ ನಾವು ಕೆಲವು ಸಿಎಸ್ಎಸ್ fundamentals elementsಗಳನ್ನು ಅನ್ವೇಷಿಸಿದ್ದೇವೆ,  **style.css**  ಫೈಲ್‌ಗೆ ಹೆಚ್ಚಿನ ನಿಯಮಗಳು ಮತ್ತು ಮಾಹಿತಿಯನ್ನು ಸೇರಿಸುವ ಮೂಲಕ ಉದಾಹರಣೆಯ ನೋಟವನ್ನು ಸುಧಾರಿಸೋಣ.

1.  ಮೊದಲಿಗೆ, ನಿಮ್ಮ ವೆಬ್‌ಸೈಟ್ ಹೇಗಿರುತ್ತದೆ ಎಂದು ನೀವು ಈ ಹಿಂದೆ ಉಳಿಸಿದ output ಅನ್ನು ಹುಡುಕಿ. ನಿಮ್ಮ  **index.html**  ನ head ಒಳಗೆ ಎಲ್ಲೋ <link> ಅಂಶವನ್ನು ಸೇರಿಸಿ (<head> ಮತ್ತು </ head> ಟ್ಯಾಗ್‌ಗಳ ನಡುವೆ ಎಲ್ಲಿಯಾದರೂ). ಇದು ಈ ರೀತಿ ಕಾಣುತ್ತದೆ:  _<link href=”https://fonts.googleapis.com/css?family=Open+Sans” rel=”stylesheet”>_ ಈ ಕೋಡ್ ನಿಮ್ಮ pageನ್ನು, ವೆಬ್‌ಪುಟದೊಂದಿಗೆ Open Sans font familyನ್ನು ಲೋಡ್ ಮಾಡುವ ಸ್ಟೈಲ್ ಶೀಟ್‌ಗೆ ಲಿಂಕ್ ಮಾಡುತ್ತದೆ.
2.  ಮುಂದೆ, ನಿಮ್ಮ  **style.css**  ಫೈಲ್‌ನಲ್ಲಿ ನೀವು ಹೊಂದಿರುವ ಅಸ್ತಿತ್ವದಲ್ಲಿರುವ ನಿಯಮವನ್ನು ಅಳಿಸಿ. ಇದು ಉತ್ತಮ ಪರೀಕ್ಷೆಯಾಗಿದೆ, ಆದರೆ ಸಾಕಷ್ಟು ಕೆಂಪು textದೊಂದಿಗೆ ಮುಂದುವರಿಯಬಾರದು.
3.  ಈ ಕೆಳಗಿನ ಸಾಲುಗಳನ್ನು ಸೇರಿಸಿ (ಕೆಳಗೆ ತೋರಿಸಲಾಗಿದೆ),  **font family**  ಅಸೈನ್‌ಮೆಂಟ್ ಅನ್ನು ನಿಮ್ಮ  **font family**  ಆಯ್ಕೆಯೊಂದಿಗೆ  [What will your website look like?](https://developer.mozilla.org/en-US/Learn/Getting_started_with_the_web/What_should_your_web_site_be_like#Font)  ಈ ಲಿಂಕ್ ನಿಂದ ಬದಲಾಯಿಸಿ. property font-family ನೀವು textಗೆ ಬಳಸಲು ಬಯಸುವ ಫಾಂಟ್ (ಗಳನ್ನು) ಅನ್ನು ಸೂಚಿಸುತ್ತದೆ. ಈ ನಿಯಮವು ಇಡೀ ಪುಟಕ್ಕೆ global base font ಮತ್ತು font size ನ್ನು ವ್ಯಾಖ್ಯಾನಿಸುತ್ತದೆ. <html> ಇಡೀ ಪುಟದ parent element ಆಗಿರುವುದರಿಂದ, ಅದರೊಳಗಿನ ಎಲ್ಲಾ elementsಗಳು ಒಂದೇ  **font size**  ಮತ್ತು  **font familyನ್ನು**  ಪಡೆದುಕೊಳ್ಳುತ್ತವೆ.

html {

font-size: 10px; /* px means “pixels”: the base font size is now 10 pixels high */

font-family: “Open Sans”, sans-serif; /* this should be the rest of the output you got from Google fonts */

}

**ಗಮನಿಸಿ:**  / * ಮತ್ತು * / ನಡುವಿನ ಸಿಎಸ್ಎಸ್ನಲ್ಲಿ ಯಾವುದಾದರೂ ಒಂದು ಸಿಎಸ್ಎಸ್ ಕಾಮೆಂಟ್(CSS Comment) ಆಗಿದೆ. ಕೋಡ್ ಅನ್ನು ನಿರೂಪಿಸುವಾಗ ಬ್ರೌಸರ್ ಕಾಮೆಂಟ್‌ಗಳನ್ನು ನಿರ್ಲಕ್ಷಿಸುತ್ತದೆ. ನಿಮ್ಮ ಕೋಡ್ ಬಗ್ಗೆ ಬರೆಯಲು ಸಿಎಸ್ಎಸ್ ಕಾಮೆಂಟ್‌ಗಳು ಒಂದು ಮಾರ್ಗವಾಗಿದೆ.

ಈಗ HTML bodyಒಳಗೆ ಪದವನ್ನು ಹೊಂದಿರುವ ಅಂಶಗಳಿಗಾಗಿ font-sizeಗಳನ್ನು ಹೊಂದಿಸೋಣ (<h1>, <li> ಮತ್ತು <p>). ನಾವು ಶೀರ್ಷಿಕೆಯನ್ನು ಕೇಂದ್ರೀಕರಿಸುತ್ತೇವೆ. ಅಂತಿಮವಾಗಿ, body ವಿಷಯವನ್ನು ಹೆಚ್ಚು ಓದಬಲ್ಲಂತೆ ಮಾಡಲು line height ಮತ್ತು line height ದ ಸೆಟ್ಟಿಂಗ್‌ಗಳೊಂದಿಗೆ ಎರಡನೇ ರೂಲ್‌ಸೆಟ್ ಅನ್ನು (ಕೆಳಗೆ) ವಿಸ್ತರಿಸೋಣ.

h1 {

font-size: 60px;

text-align: center;

}

p, li {

font-size: 16px;

line-height: 2;

letter-spacing: 1px;

}

ನೀವು ಇಷ್ಟಪಡುವಂತೆ px valueಗಳನ್ನು ಹೊಂದಿಸಿ. ನಿಮ್ಮ ಕಾರ್ಯ ಪ್ರಗತಿಯು ಇದಕ್ಕೆ ಹೋಲುತ್ತದೆ.

![Image for post](https://miro.medium.com/max/54/0*HqUjjxu-VtdnFjYW?q=20)

![Image for post](https://miro.medium.com/max/1000/0*HqUjjxu-VtdnFjYW)

**___________________________________________________________________________________________**

**ಸಿಎಸ್ಎಸ್(CSS): ಪೆಟ್ಟಿಗೆಗಳ ಬಗ್ಗೆ(all about boxes)**

ಸಿಎಸ್ಎಸ್ ನಲ್ಲಿ boxes ಬಗ್ಗೆ define ಮಾಡಲಾಗಿದೆ. ಇದು size, color ಮತ್ತು positionನ್ನು ಸೆಟ್ ಮಾಡೋದನ್ನು ಒಳಗೊಂಡಿದೆ. ನಿಮ್ಮ ಪುಟದಲ್ಲಿನ ಹೆಚ್ಚಿನ HTML elementsಗಳನ್ನು ಇತರ boxಗಳ ಮೇಲೆ ಕುಳಿತುಕೊಳ್ಳುವ boxಗಳೆಂದು ಭಾವಿಸಬಹುದು.

![Image for post](https://miro.medium.com/max/60/0*4UnXXFUDEOmvvRuP?q=20)

![Image for post](https://miro.medium.com/max/281/0*4UnXXFUDEOmvvRuP)

ಸಿಎಸ್ಎಸ್ ವಿನ್ಯಾಸವು ಹೆಚ್ಚಾಗಿ ಬಾಕ್ಸ್ ಮಾದರಿಯನ್ನು ಆಧರಿಸಿದೆ. ನಿಮ್ಮ ಪುಟದಲ್ಲಿ ಜಾಗವನ್ನು ತೆಗೆದುಕೊಳ್ಳುವ ಪ್ರತಿಯೊಂದು ಪೆಟ್ಟಿಗೆಯೂ ಈ ರೀತಿಯ ಗುಣಲಕ್ಷಣಗಳನ್ನು ಹೊಂದಿದೆ:

-   **ಪ್ಯಾಡಿಂಗ್(padding),**  ವಿಷಯದ ಸುತ್ತಲಿನ ಸ್ಥಳ. ಕೆಳಗಿನ ಉದಾಹರಣೆಯಲ್ಲಿ, ಇದು ಪ್ಯಾರಾಗ್ರಾಫ್ text ನ ಸುತ್ತಲಿನ ಸ್ಥಳವಾಗಿದೆ.
-   **ಗಡಿ(border),**  ಪ್ಯಾಡಿಂಗ್‌ನ ಹೊರಗಿರುವ ಘನ ರೇಖೆ.
-   **ಅಂಚು(margin),**  ಗಡಿಯ ಹೊರಭಾಗದಲ್ಲಿರುವ ಸ್ಥಳ.

![Image for post](https://miro.medium.com/max/60/0*n6WdsiJbBkEjl7_t?q=20)

![Image for post](https://miro.medium.com/max/404/0*n6WdsiJbBkEjl7_t)

ಈ ವಿಭಾಗದಲ್ಲಿ ನಾವು ಸಹ ಬಳಸುತ್ತೇವೆ:

-   **width**  (of an element).
-   **background-color,**  ಒಂದು element content ಮತ್ತು ಪ್ಯಾಡಿಂಗ್ ಹಿಂದಿನ ಬಣ್ಣ.
-   **color,**  ಒಂದು element content ನ ಬಣ್ಣ (ಸಾಮಾನ್ಯವಾಗಿ text).
-   **text-shadow**  ಒಂದು element ಒಳಗಿನ text ಗೆ drop shadowವನ್ನು ಸೆಟ್ ಮಾಡಲಾಗುತ್ತದೆ
-   **display,**  ಒಂದು elenmentನ display ಮೋಡ್ ಅನ್ನು ಹೊಂದಿಸುತ್ತದೆ.

**Style.css**  ನ ಕೆಳಭಾಗದಲ್ಲಿ ಈ ಹೊಸ ನಿಯಮಗಳನ್ನು ಸೇರಿಸುತ್ತಲೇ ಇರಿ. ಏನಾಗುತ್ತದೆ ಎಂದು ನೋಡಲು valueಗಳನ್ನು ಬದಲಾಯಿಸುವ ಪ್ರಯೋಗ.

**ಪುಟದ**  **ಬಣ್ಣವನ್ನು**  **ಬದಲಾಯಿಸುವುದು(changing the page color)**

html {

background-color: #00539F;

}

ಈ ನಿಯಮವು ಇಡೀ ಪುಟಕ್ಕೆ background-colorನ್ನು ಹೊಂದಿಸುತ್ತದೆ. ಕಲರ್ ಕೋಡ್ ಚೇಂಜ್ ಮಾಡಲು ಈ ಲಿಂಕ್ ನ್ನು ನೋಡಿ  [the color you chose in What will my website look like?](https://developer.mozilla.org/en-US/Learn/Getting_started_with_the_web/What_should_your_web_site_be_like#Theme_color)

**Bodyನ್ನು**  **ವಿನ್ಯಾಸಗೊಳಿಸುವುದು(Styling the body)**

body {

width: 600px;

margin: 0 auto;

background-color: #FF9500;

padding: 0 20px 20px 20px;

border: 5px solid black;

}

<body> element ಗಾಗಿ ಹಲವಾರು declarationಗಳಿವೆ.

-   width: 600px; ಇದು bodyನ್ನು ಯಾವಾಗಲೂ 600 ಪಿಕ್ಸೆಲ್‌ಗಳಷ್ಟು ಅಗಲವಾಗಿರಲು ಒತ್ತಾಯಿಸುತ್ತದೆ.
-   margin: 0 auto; ಅಂಚು ಅಥವಾ ಪ್ಯಾಡಿಂಗ್‌ನಂತಹ propertyಯಲ್ಲಿ ನೀವು ಎರಡು valueಗಳನ್ನು ಹೊಂದಿಸಿದಾಗ, ಮೊದಲ valueವು element ಮೇಲಿನ ಮತ್ತು ಕೆಳಗಿನ ಭಾಗದ ಮೇಲೆ ಪರಿಣಾಮ ಬೀರುತ್ತದೆ (ಈ ಸಂದರ್ಭದಲ್ಲಿ ಅದನ್ನು 0 ಗೆ ಹೊಂದಿಸುವುದು); ಎರಡನೆಯvalueವು ಎಡ ಮತ್ತು ಬಲ ಭಾಗದ ಮೇಲೆ ಪರಿಣಾಮ ಬೀರುತ್ತದೆ. (ಇಲ್ಲಿ, auto ಎನ್ನುವುದು ಲಭ್ಯವಿರುವ ಸಮತಲ ಜಾಗವನ್ನು ಎಡ ಮತ್ತು ಬಲಕ್ಕೆ ಸಮನಾಗಿ ವಿಭಜಿಸುವ ವಿಶೇಷ valueವಾಗಿದೆ). ಮಾರ್ಜಿನ್ ಸಿಂಟ್ಯಾಕ್ಸ್ನಲ್ಲಿ ದಾಖಲಾಗಿರುವಂತೆ ನೀವು ಒಂದು, ಮೂರು ಅಥವಾ ನಾಲ್ಕು valueಗಳನ್ನು ಸಹ ಬಳಸಬಹುದು.
-   background-color: #FF9500; ಇದು elementನ background colorನ್ನು ಹೊಂದಿಸುತ್ತದೆ. <html> elementಗೆ dark ನೀಲಿ ಬಣ್ಣಕ್ಕೆ ವಿರುದ್ಧವಾಗಿ ಈ ಯೋಜನೆಯು body ಯ background colorಗಾಗಿ ಕೆಂಪು ಕಿತ್ತಳೆ ಬಣ್ಣವನ್ನು ಬಳಸುತ್ತದೆ. (ಪ್ರಯೋಗ ಮಾಡಲು ಹಿಂಜರಿಯಬೇಡಿ.)
-   padding: 0 20px 20px 20px; ಇದು ಪ್ಯಾಡಿಂಗ್‌ಗೆ ನಾಲ್ಕು valueಗಳನ್ನು ಹೊಂದಿಸುತ್ತದೆ. ವಿಷಯದ ಸುತ್ತ ಸ್ವಲ್ಪ ಜಾಗವನ್ನು ಹಾಕುವುದು ಗುರಿಯಾಗಿದೆ. ಈ ಉದಾಹರಣೆಯಲ್ಲಿ, body ಮೇಲ್ಭಾಗದಲ್ಲಿ ಯಾವುದೇ ಪ್ಯಾಡಿಂಗ್ ಇಲ್ಲ, ಮತ್ತು ಬಲ, ಕೆಳಗಿನ ಮತ್ತು ಎಡಭಾಗದಲ್ಲಿ 20 ಪಿಕ್ಸೆಲ್‌ಗಳು ಇಲ್ಲ. valueಗಳು ಆ ಕ್ರಮದಲ್ಲಿ ಮೇಲಿನ, ಬಲ, ಕೆಳಗಿನ, ಎಡಕ್ಕೆ ಹೊಂದಿಸಲ್ಪಡುತ್ತವೆ. marginನಂತೆ, ಪ್ಯಾಡಿಂಗ್ ಸಿಂಟ್ಯಾಕ್ಸ್‌ನಲ್ಲಿ([Padding Syntax](https://developer.mozilla.org/en-US/docs/Web/CSS/padding#Syntax)) ದಾಖಲಾಗಿರುವಂತೆ ನೀವು ಒಂದು, ಎರಡು, ಮೂರು ಅಥವಾ ನಾಲ್ಕು valueಗಳನ್ನು ಬಳಸಬಹುದು.
-   border: 5px solid black; ಇದು border width, style ಮತ್ತು color ಗೆ valueಗಳನ್ನು ಹೊಂದಿಸುತ್ತದೆ. ಈ ಸಂದರ್ಭದಲ್ಲಿ, ಇದು bodyಯ ಎಲ್ಲಾ ಬದಿಗಳಲ್ಲಿ ಐದು ಪಿಕ್ಸೆಲ್ ಅಗಲ, ಕಪ್ಪು border ಆಗಿ ಸೆಟ್ ಮಾಡುತ್ತದೆ.

**ಮುಖ್ಯ**  **ಪುಟದ**  **ಶೀರ್ಷಿಕೆಯನ್ನು**  **ಇರಿಸುವುದು**  **ಮತ್ತು**  **ವಿನ್ಯಾಸಗೊಳಿಸುವುದು(positioning and styling the main page title)**

h1 {

margin: 0;

padding: 20px 0;

color: #00539F;

text-shadow: 3px 3px 1px black;

}

body ಮೇಲ್ಭಾಗದಲ್ಲಿ horrible gapದೆ ಎಂದು ನೀವು ಗಮನಿಸಿರಬಹುದು. ಅದು ಸಂಭವಿಸುತ್ತದೆ ಏಕೆಂದರೆ ಬ್ರೌಸರ್‌ಗಳು default ಸ್ಟೈಲಿಂಗ್ ಅನ್ನು <h1> elementಗೆ ಅನ್ವಯಿಸುತ್ತವೆ . ಅದು ಕೆಟ್ಟ ಆಲೋಚನೆಯಂತೆ ಕಾಣಿಸಬಹುದು, ಆದರೆ unstyled pageಗಳಿಗೆ basic readabilityಯನ್ನು ಒದಗಿಸುವುದು ಇದರ ಉದ್ದೇಶ. ಅಂತರವನ್ನು ತೆಗೆದುಹಾಕಲು, ನಾವು ಬ್ರೌಸರ್‌ನ ಡೀಫಾಲ್ಟ್ ಸ್ಟೈಲಿಂಗ್ ಅನ್ನು ಸೆಟ್ಟಿಂಗ್ marginಗಳೊಂದಿಗೆ ತಿದ್ದಿ ಬರೆಯುತ್ತೇವೆ: margin: 0;.

ಮುಂದೆ, ನಾವು heading ಮೇಲಿನ ಮತ್ತು ಕೆಳಗಿನ ಪ್ಯಾಡಿಂಗ್ ಅನ್ನು 20 ಪಿಕ್ಸೆಲ್‌ಗಳಿಗೆ ಹೊಂದಿಸಿದ್ದೇವೆ.

ಅದನ್ನು ಅನುಸರಿಸಿ, ನಾವು heading textನ್ನು HTML background-color ಒಂದೇ ಬಣ್ಣಕ್ಕೆ ಹೊಂದಿಸಿದ್ದೇವೆ.

ಅಂತಿಮವಾಗಿ, text-shadow elementನ text content ಗೆ ನೆರಳು ಅನ್ವಯಿಸುತ್ತದೆ. ಇದರ ನಾಲ್ಕು valueಗಳು:

-   ಮೊದಲ ಪಿಕ್ಸೆಲ್ valueವು textದಿಂದ ನೆರಳಿನ  **horizontal offset**  ಅನ್ನು ಹೊಂದಿಸುತ್ತದೆ: ಅದು ಎಷ್ಟು ದೂರಕ್ಕೆ ಚಲಿಸುತ್ತದೆ.(how far it moves across.)
-   ಎರಡನೇ ಪಿಕ್ಸೆಲ್ valueವು ಪದದಿಂದ ನೆರಳಿನ  **vertical offset**  ಅನ್ನು ಹೊಂದಿಸುತ್ತದೆ: ಅದು ಎಷ್ಟು ದೂರಕ್ಕೆ ಚಲಿಸುತ್ತದೆ.(how far it moves down.)
-   ಮೂರನೇ ಪಿಕ್ಸೆಲ್ valueವು ನೆರಳಿನ  **blur radius**  ನ್ನು ಹೊಂದಿಸುತ್ತದೆ. ದೊಡ್ಡ valueವು ಹೆಚ್ಚು ಅಸ್ಪಷ್ಟವಾಗಿ ಕಾಣುವ ನೆರಳು ನೀಡುತ್ತದೆ.
-   ನಾಲ್ಕನೆಯ valueವು ನೆರಳಿನ ಮೂಲ ಬಣ್ಣವನ್ನು( base color) ಹೊಂದಿಸುತ್ತದೆ.

ಅದು ಹೇಗೆ ನೋಟವನ್ನು ಬದಲಾಯಿಸುತ್ತದೆ ಎಂಬುದನ್ನು ನೋಡಲು ವಿಭಿನ್ನ valueಗಳೊಂದಿಗೆ ಪ್ರಯೋಗಿಸಲು ಪ್ರಯತ್ನಿಸಿ.

**ಚಿತ್ರವನ್ನು**  **ಕೇಂದ್ರೀಕರಿಸಲಾಗುತ್ತಿದೆ(centering the image)**

img {

display: block;

margin: 0 auto;

}

ಮುಂದೆ, ಚಿತ್ರವು ಉತ್ತಮವಾಗಿ ಕಾಣುವಂತೆ ನಾವು ಅದನ್ನು ಕೇಂದ್ರೀಕರಿಸುತ್ತೇವೆ. ನಾವು bodyಗೆ ಮಾಡಿದಂತೆ ನಾವು  **margin: 0 auto**  ಟ್ರಿಕ್ ಅನ್ನು ಮತ್ತೆ ಬಳಸಬಹುದು. ಆದರೆ ಸಿಎಸ್ಎಸ್ ಕೆಲಸ ಮಾಡಲು ಹೆಚ್ಚುವರಿ ಸೆಟ್ಟಿಂಗ್ ಅಗತ್ಯವಿರುವ ವ್ಯತ್ಯಾಸಗಳಿವೆ.

<body> ಒಂದು  **block**  element ಆಗಿದೆ, ಅಂದರೆ ಅದು ಪುಟದಲ್ಲಿ ಜಾಗವನ್ನು ತೆಗೆದುಕೊಳ್ಳುತ್ತದೆ. block elementವು margin ಮತ್ತು ಇತರ spacing valuesಗಳನ್ನು ಹೊಂದಿರಬಹುದು. ಇದಕ್ಕೆ ವಿರುದ್ಧವಾಗಿ, ಚಿತ್ರಗಳು  **inline** ​​elementಗಳಾಗಿವೆ. ಇನ್ಲೈನ್ ​​ಅಂಶಗಳಿಗೆ margin ಅಥವಾ spacing valuesಗಳನ್ನು ಅನ್ವಯಿಸಲು ಸಾಧ್ಯವಿಲ್ಲ. ಆದ್ದರಿಂದ ಚಿತ್ರಕ್ಕೆ marginಗಳನ್ನು ಅನ್ವಯಿಸಲು, ನಾವು displayನ್ನು ಬಳಸಿಕೊಂಡು ಇಮೇಜ್ ಬ್ಲಾಕ್-ಮಟ್ಟದ ನಡವಳಿಕೆಯನ್ನು ನೀಡಬೇಕು: display: block;.

ಗಮನಿಸಿ: ಮೇಲಿನ ಸೂಚನೆಗಳು ನೀವು body ಮೇಲೆ ಹೊಂದಿಸಿರುವ ಅಗಲಕ್ಕಿಂತ ಚಿಕ್ಕದಾದ ಚಿತ್ರವನ್ನು ಬಳಸುತ್ತಿರುವಿರಿ ಎಂದು ಊಹಿಸುತ್ತದೆ. (600 ಪಿಕ್ಸೆಲ್‌ಗಳು) ನಿಮ್ಮ ಚಿತ್ರ ದೊಡ್ಡದಾಗಿದ್ದರೆ, it overflow the body, ಉಳಿದ ಪುಟಗಳಿಗೆ ಚೆಲ್ಲುತ್ತದೆ. ಇದನ್ನು ಸರಿಪಡಿಸಲು, ನೀವು ಇದನ್ನು ಮಾಡಬಹುದು: 1) ಗ್ರಾಫಿಕ್ಸ್ ಸಂಪಾದಕವನ್ನು ಬಳಸಿಕೊಂಡು ಚಿತ್ರದ widthನ್ನು ಕಡಿಮೆ ಮಾಡಿ, ಅಥವಾ 2) <img> elements width propertyಯನ್ನು ಸಣ್ಣ valueದೊಂದಿಗೆ ಹೊಂದಿಸುವ ಮೂಲಕ ಚಿತ್ರದ sizeಗೆ CSS ಬಳಸಿ.

ಗಮನಿಸಿ: display:block; ಅಥವಾ ಬ್ಲಾಕ್ ಅಂಶ ಮತ್ತು ಇನ್ಲೈನ್ ​​elements ನಡುವಿನ ವ್ಯತ್ಯಾಸಗಳು ಸಂಪೂರ್ಣವಾಗಿ ಅರ್ಥಮಾಡಿಕೊಳ್ಳದಿದ್ದರೆ ಹೆಚ್ಚು ಕಾಳಜಿ ವಹಿಸಬೇಡಿ:. ನಿಮ್ಮ ಸಿಎಸ್ಎಸ್ ಅಧ್ಯಯನವನ್ನು ನೀವು ಮುಂದುವರಿಸುವುದರಿಂದ ಇದು ಹೆಚ್ಚು ಅರ್ಥವನ್ನು ನೀಡುತ್ತದೆ. ಎಂಡಿಎನ್‌ನ ಪ್ರದರ್ಶನ ಉಲ್ಲೇಖ ಪುಟದಲ್ಲಿ ವಿಭಿನ್ನ ಪ್ರದರ್ಶನ valueಗಳ ಕುರಿತು ಹೆಚ್ಚಿನ ಮಾಹಿತಿಯನ್ನು ನೀವು ಕಾಣಬಹುದು.

**ತೀರ್ಮಾನ (Conclusion)**

ಈ ಲೇಖನದ ಎಲ್ಲಾ ಸೂಚನೆಗಳನ್ನು ನೀವು ಅನುಸರಿಸಿದರೆ, ನೀವು ಈ ಪುಟವನ್ನು ಹೋಲುವ ಪುಟವನ್ನು ಹೊಂದಿರಬೇಕು:

![Image for post](https://miro.medium.com/max/52/0*JdcWs4Zz1RLbXGnY?q=20)

![Image for post](https://miro.medium.com/max/1000/0*JdcWs4Zz1RLbXGnY)

(ನೀವು ನಮ್ಮ ಆವೃತ್ತಿಯನ್ನು ಇಲ್ಲಿ ವೀಕ್ಷಿಸಬಹುದು  [view our version here](http://mdn.github.io/beginner-html-site-styled/).) ನೀವು ಸಿಲುಕಿಕೊಂಡರೆ, ನಿಮ್ಮ ಕೆಲಸವನ್ನು ನೀವು ಯಾವಾಗಲೂ ಗಿಟ್‌ಹಬ್‌ನಲ್ಲಿನ ನಮ್ಮ ಸಿದ್ಧಪಡಿಸಿದ ಉದಾಹರಣೆ ಕೋಡ್‌ನೊಂದಿಗೆ ಹೋಲಿಸಬಹುದು. ([finished example code on GitHub](https://github.com/mdn/beginner-html-site-styled/blob/gh-pages/styles/style.css))

ಈ exerciseಲ್ಲಿ, ನಾವು ಸಿಎಸ್ಎಸ್ನ ಮೇಲ್ಮೈಯನ್ನು ಗೀಚಿದ್ದೇವೆ. ಮುಂದೆ ಹೋಗಲು,  [Learning to style HTML using CSS](https://developer.mozilla.org/en-US/Learn/CSS)  ನೋಡಿ.

**Article By: Hemalatha**

Credits:  [https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)

MicroDegree is an edtech platform for learning Emerging Technologies such as Full-Stack Development, Data Science, Machine Learning using vernacular at an affordable price. For more details reach out to hello@microdegree.work

🚀 For Course Certification : [https://bit.ly/3gt2nY7](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqblAzcGQxZlRtSmdYZlppbDNUd2t0MFNSanV1QXxBQ3Jtc0tuS2VjaXpMd1hFS1I5NEFuMkxkYThlZE9MZkVzNGFmTXYxTTRtZjBsX0lkSTU3MEpEdnpCTnI3MUp2QVpNdWc0LXBjNEpVWEVhMTBuajBEeXRiMnZSWnpFVDJHMTlCRk91bkNpR24ySGxUSzJUblNfUQ%3D%3D&q=https%3A%2F%2Fbit.ly%2F3gt2nY7)

👍 Youtube:: [https://bit.ly/3ajK4Cz](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqbDlUVFVtUVN1Wnl0Z3lpZ19aUVV5ZVU1SWQyQXxBQ3Jtc0tuamNVOWJCVkdsNmwzcEF2VG1XS0cwYmZWekJVbFp2enBldkg1WUEzUm1iSkZuV0ZzbGduSG8tSXlRM1N1bzRtR1BCMGN2cTJMekJSS0xzVE9pdFBrd2hpNUV5SDQ5dl9sSFFYbERzQ1NNdU5CWWU4WQ%3D%3D&q=https%3A%2F%2Fbit.ly%2F3ajK4Cz)

Website : [https://microdegree.work](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqbjR2M3JJekdSZTZlTVFCNkt5RFBTc1JNMlhpUXxBQ3Jtc0tuZHhRdjZtQW9ubmliWXAxSVNfMm5UemNrS2RMd1hDMmtIdEdGcmlFZmpkTDRkV1JFbkl3Wng1b2NRSXZJeWVlMjFGWmRpWmJSUU5jTGZmMFA0NTMxRUJtTnBlVlNESUdDYlA1QU4tcUdzZ1gwZHFUWQ%3D%3D&q=https%3A%2F%2Fmicrodegree.work)

LinkedIn : [https://www.linkedin.com/company/micr](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqa1Z1SEw5M182a2I3ZC1BN25WeFdYYVNaRWkzQXxBQ3Jtc0tsTmlGQkN5RExFekhvWWFjVHJEZUZadVZVNW5NTURjYkxaSWlVTzFJaVU0aUJ3Q1Y1QXZaRU5sbEJFaVpiOUp6a3V4a3dZczVlSVA4SzVvYU1Jc3A3SEVUMkROUEpNeFFSNkxrbldZOVhTQTBUQWdFbw%3D%3D&q=https%3A%2F%2Fwww.linkedin.com%2Fcompany%2Fmicr)...

Facebook : [https://www.facebook.com/microdegree](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqa3BNeV9oRnNsVmdiMW1malJ4M3M2REVXUVItUXxBQ3Jtc0tsN0V6MXIxOXRCSU9DMDVBQm0wemEyMnFWMWRNQVRNNlNxX2ZwOHdQLWRUWVQ1SnBSR3JFLUFnLV9VS2FYdk9QQ0x5MjZZOEMyV2JkV2o2emNVMHhZVEZUbDRKdTBoVnBXS3FGNERiZkN3aFNXOF9Xbw%3D%3D&q=https%3A%2F%2Fwww.facebook.com%2Fmicrodegree)

Instagram : [https://www.instagram.com/micro.degree](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqbU82YjFKOFBrMXZ4QkRrWWtlbTlzV1VvU1g1QXxBQ3Jtc0trYndfRGt1cUtVS3ZUaFRkVEJtSUd4M1VJTndfR2s1WDQ0Y3Axd0dXdzN1eVRNZHF2VEo5MFhyZkkxRmVXcXJZMUN0X1dXYTZsY1RyNS11OVJWWG0zd0ZKX1EzcXJMSFU4Tnd2QzF6dUJYLTdrZW0zaw%3D%3D&q=https%3A%2F%2Fwww.instagram.com%2Fmicro.degree)