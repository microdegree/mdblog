---
title: 'HTMLBasic'
author: [Ghost]
tags: []
image: img/marvin-meyer-794521-unsplash.jpg
date: '2020-11-04T10:00:00.000Z'
draft: false
---


**HTML ಮೂಲಗಳು**

ಎಚ್ಟಿಎಮ್ಎಲ್ (ಹೈಪರ್ಟೆಕ್ಸ್ಟ್ ಮಾರ್ಕಪ್ ಲಾಂಗ್ವೇಜ್) ಎನ್ನುವುದು ವೆಬ್ page ಮತ್ತು ಅದರ contentನ್ನು ರಚಿಸಲು ಬಳಸುವ ಕೋಡ್ ಆಗಿದೆ. ಉದಾಹರಣೆಗೆ, contentನ್ನು ಪ್ಯಾರಾಗ್ರಾಫ್‌ಗಳ ಗುಂಪಿನಲ್ಲಿ, ಬುಲೆಟೆಡ್ ಪಾಯಿಂಟ್‌ಗಳ ಪಟ್ಟಿಯಲ್ಲಿ ಅಥವಾ ಚಿತ್ರಗಳು ಮತ್ತು ಡೇಟಾ ಟೇಬಲ್‌ಗಳನ್ನು ಬಳಸಿ ರಚಿಸಬಹುದು. ಶೀರ್ಷಿಕೆಯು ಸೂಚಿಸುವಂತೆ, ಈ ಲೇಖನವು ನಿಮಗೆ HTML ಮತ್ತು ಅದರ ಕಾರ್ಯಗಳ ಬಗ್ಗೆ ಮೂಲಭೂತ ತಿಳುವಳಿಕೆಯನ್ನು ನೀಡುತ್ತದೆ.

**ಹಾಗಾದರೆ HTML ಎಂದರೇನು?**

ಎಚ್ಟಿಎಮ್ಎಲ್ ಪ್ರೋಗ್ರಾಮಿಂಗ್ ಭಾಷೆಯಲ್ಲ; ಇದು ನಿಮ್ಮ content ರಚನೆಯನ್ನು ವ್ಯಾಖ್ಯಾನಿಸುವ ಮಾರ್ಕ್ಅಪ್ Language. ಎಚ್ಟಿಎಮ್ಎಲ್ Elements ಸರಣಿಯನ್ನು ಒಳಗೊಂಡಿರುತ್ತದೆ, ಅದು contentನ ವಿವಿಧ ಭಾಗಗಳನ್ನು ಒಂದು ನಿರ್ದಿಷ್ಟ ರೀತಿಯಲ್ಲಿ ಗೋಚರಿಸುವಂತೆ ಮಾಡಲು ಅಥವಾ ನಿರ್ದಿಷ್ಟ ರೀತಿಯಲ್ಲಿ ಕಾರ್ಯನಿರ್ವಹಿಸಲು ನೀವು ಬಳಸುತ್ತೀರಿ. ಸುತ್ತುವರಿದ ಟ್ಯಾಗ್‌ಗಳು word ಅಥವಾ ಇಮೇಜ್ ಅನ್ನು ಬೇರೆಡೆಗೆ ಹೈಪರ್ಲಿಂಕ್ ಮಾಡಬಹುದು, ಪದಗಳನ್ನು ಇಟಲೈಸ್ ಮಾಡಬಹುದು, ಫಾಂಟ್ ಅನ್ನು ದೊಡ್ಡದಾಗಿ ಅಥವಾ ಚಿಕ್ಕದಾಗಿ ಮಾಡಬಹುದು. ಉದಾಹರಣೆಗೆ, ಈ ಕೆಳಗಿನ ವಿಷಯವನ್ನು ತೆಗೆದುಕೊಳ್ಳಿ:

My cat is very grumpy

ರೇಖೆಯು ತಾನಾಗಿಯೇ ನಿಲ್ಲಬೇಕೆಂದು ನಾವು ಬಯಸಿದರೆ, ಅದನ್ನು ಪ್ಯಾರಾಗ್ರಾಫ್ ಟ್ಯಾಗ್‌ಗಳಲ್ಲಿ ಸುತ್ತುವ ಮೂಲಕ ಪ್ಯಾರಾಗ್ರಾಫ್ ಎಂದು ನಾವು ನಿರ್ದಿಷ್ಟಪಡಿಸಬಹುದು:

<p>My cat is very grumpy</p>

**HTML ಎಲಿಮೆಂಟ್ ಅನಾಟಮಿ/ಅಂಗರಚನಾಶಾಸ್ತ್ರ**

ಈ ಪ್ಯಾರಾಗ್ರಾಫ್ ಎಲಿಮೆಂಟ್ ನ್ನು ಸ್ವಲ್ಪ ಮುಂದೆ ಅನ್ವೇಷಿಸೋಣ.

![Image for post](https://miro.medium.com/max/60/0*RdDaMYAci8ux4TeS?q=20)

ನಮ್ಮ ಎಲಿಮೆಂಟ್ ಮುಖ್ಯ ಭಾಗಗಳು ಹೀಗಿವೆ:

1.  **ಓಪನಿಂಗ್/ಆರಂಭಿಕ ಟ್ಯಾಗ್:**  ಇದು ಎಲಿಮೆಂಟ್ ಹೆಸರನ್ನು ಹೊಂದಿರುತ್ತದೆ (ಈ ಸಂದರ್ಭದಲ್ಲಿ, ಆಂಗಲ್ ಬ್ರಾಕೆಟ್ ಗಳನ್ನು ತೆರೆಯುವ ಮತ್ತು ಮುಚ್ಚುವಲ್ಲಿ wrap/ಸುತ್ತಿಡಲಾಗುತ್ತದೆ. ಎಲಿಮೆಂಟ್ ಎಲ್ಲಿ ಪ್ರಾರಂಭವಾಗುತ್ತದೆ ಅಥವಾ ಪರಿಣಾಮ ಬೀರಲು ಪ್ರಾರಂಭಿಸುತ್ತದೆ ಎಂದು ಇದು ಹೇಳುತ್ತದೆ — ಈ ಸಂದರ್ಭದಲ್ಲಿ ಪ್ಯಾರಾಗ್ರಾಫ್ ಪ್ರಾರಂಭವಾಗುತ್ತದೆ.
2.  **ಕ್ಲೋಸಿಂಗ್ /ಮುಕ್ತಾಯದ ಟ್ಯಾಗ್:**  ಇದು ಆರಂಭಿಕ ಟ್ಯಾಗ್‌ನಂತೆಯೇ ಇರುತ್ತದೆ, ಅದು ಎಲಿಮೆಂಟ್ ಹೆಸರಿನ ಮುಂದೆ ಫಾರ್ವರ್ಡ್ ಸ್ಲ್ಯಾಷ್ ಅನ್ನು ಒಳಗೊಂಡಿರುತ್ತದೆ. ಎಲಿಮೆಂಟ್ ಎಲ್ಲಿ ಕೊನೆಗೊಳ್ಳುತ್ತದೆ ಎಂದು ಇದು ಹೇಳುತ್ತದೆ — ಈ ಸಂದರ್ಭದಲ್ಲಿ ಪ್ಯಾರಾಗ್ರಾಫ್ ಕೊನೆಗೊಳ್ಳುತ್ತದೆ.ಮುಕ್ತಾಯದ ಟ್ಯಾಗ್ ಸೇರಿಸಲು ವಿಫಲವಾದದ್ದು ವಿಚಿತ್ರ ಫಲಿತಾಂಶಗಳಿಗೆ ಕಾರಣವಾಗಬಹುದು.
3.  **ಕಂಟೆಂಟ್ /ವಿಷಯ:**  ಇದು ಎಲಿಮೆಂಟ್ ವಿಷಯವಾಗಿದೆ, ಈ ಸಂದರ್ಭದಲ್ಲಿ ಅದು ಕೇವಲ text.
4.  **ಎಲಿಮೆಂಟ್:**  ಆರಂಭಿಕ ಟ್ಯಾಗ್, ಮುಕ್ತಾಯದ ಟ್ಯಾಗ್ ಮತ್ತು content ಒಟ್ಟಾಗಿ ಎಲಿಮೆಂಟ್ ನ್ನು ಒಳಗೊಂಡಿರುತ್ತದೆ.

ಎಲಿಮೆಂಟ್ ಈ ಕೆಳಗಿನಂತೆ ಕಾಣುವ ಅಟ್ರಿಬ್ಯೂಟ್ಸ್ ನ್ನು ಸಹ ಹೊಂದಬಹುದು:

![Image for post](https://miro.medium.com/max/60/0*KjAs3SiIz1omsJyf?q=20)

ಅಟ್ರಿಬ್ಯೂಟ್ಸ್ ನೀವು ನಿಜವಾದ ವಿಷಯದಲ್ಲಿ ಕಾಣಿಸಿಕೊಳ್ಳಲು ಇಷ್ಟಪಡದ ಎಲಿಮೆಂಟ್ ಕುರಿತು ಹೆಚ್ಚುವರಿ ಮಾಹಿತಿಯನ್ನು ಒಳಗೊಂಡಿರುತ್ತವೆ. ಇಲ್ಲಿ, class ಅನ್ನುವುದು ಅಟ್ರಿಬ್ಯೂಟ್ಸ್ ಹೆಸರು ಮತ್ತು editor-note/ಸಂಪಾದಕ-ಟಿಪ್ಪಣಿ ಅಟ್ರಿಬ್ಯೂಟ್ಸ್ ವ್ಯಾಲ್ಯೂವಾಗಿದೆ.

ಅಟ್ರಿಬ್ಯೂಟ್ಸ್ ಯಾವಾಗಲೂ ಈ ಕೆಳಗಿನವುಗಳನ್ನು ಹೊಂದಿರಬೇಕು:

1.  ಅದರ ಮತ್ತು ಎಲಿಮೆಂಟ್ ಹೆಸರಿನ ನಡುವಿನ ಸ್ಥಳ (ಅಥವಾ ಹಿಂದಿನ ಅಟ್ರಿಬ್ಯೂಟ್ಸ್, ಎಲಿಮೆಂಟ್ ಈಗಾಗಲೇ ಒಂದು ಅಥವಾ ಹೆಚ್ಚಿನ ಅಟ್ರಿಬ್ಯೂಟ್ಸ್ ನ್ನು ಹೊಂದಿದ್ದರೆ).
2.  ಅಟ್ರಿಬ್ಯೂಟ್ಸ್ ಹೆಸರು ನಂತರ ಸಮಾನ ಚಿಹ್ನೆ/Equal Sign.
3.  Quotation mark/ ಉದ್ಧರಣ ಚಿಹ್ನೆಗಳನ್ನು ತೆರೆಯುವ ಮತ್ತು ಮುಚ್ಚುವ ಮೂಲಕ ಅಟ್ರಿಬ್ಯೂಟ್ಸ್ ವ್ಯಾಲ್ಯೂವನ್ನು ಸುತ್ತಿಡಲಾಗುತ್ತದೆ.

**ನೆಸ್ಟಿಂಗ್ ಎಲಿಮೆಂಟ್ಸ್**

ನೀವು ಇತರ elements ಒಳಗೆ elementsನ್ನು ಹಾಕಬಹುದು — ಇದನ್ನು ನೆಸ್ಟಿಂಗ್ ಎಂದು ಕರೆಯಲಾಗುತ್ತದೆ. ನಮ್ಮ ಬೆಕ್ಕು ತುಂಬಾ ಮುಂಗೋಪದದ್ದಾಗಿದೆ ಎಂದು ನಾವು ಹೇಳಲು ಬಯಸಿದರೆ, ನಾವು “ತುಂಬಾ” ಎಂಬ ಪದವನ್ನು <strong> elementsಲ್ಲಿ ಸುತ್ತಿಕೊಳ್ಳಬಹುದು, ಇದರರ್ಥ ಈ wordನ್ನು ಬಲವಾಗಿ ಒತ್ತಿ ಹೇಳಬೇಕು:

<p>My cat is <strong>very</strong> grumpy.</p>

ನಿಮ್ಮ elements ಸರಿಯಾಗಿ ನೆಸ್ಟಿಂಗ್ ಆಗಿದೆಯೇ ಎಂದು ನೀವು ಖಚಿತಪಡಿಸಿಕೊಳ್ಳಬೇಕು. ಮೇಲಿನ ಉದಾಹರಣೆಯಲ್ಲಿ, ನಾವು ಮೊದಲು <p> elementನ್ನು ತೆರೆದಿದ್ದೇವೆ, ನಂತರ <strong> element; ಆದ್ದರಿಂದ, ನಾವು ಮೊದಲು <strong> elementನ್ನು, ನಂತರ <p> elementನ್ನು ಮುಚ್ಚಬೇಕು. ಕೆಳಗಿನವು ತಪ್ಪಾಗಿದೆ:

<p>My cat is <strong>very grumpy.</p></strong>

element ಒಂದಕ್ಕೊಂದು ಒಳಗೆ ಅಥವಾ ಹೊರಗೆ ಸ್ಪಷ್ಟವಾಗಿ ಇರುವಂತೆ ಸರಿಯಾಗಿ ತೆರೆಯಬೇಕು ಮತ್ತು ಮುಚ್ಚಬೇಕು. ಮೇಲೆ ತೋರಿಸಿರುವಂತೆ ಅವು ಅತಿಕ್ರಮಿಸಿದರೆ, ನಿಮ್ಮ ವೆಬ್ ಬ್ರೌಸರ್ ನೀವು ಹೇಳಲು ಪ್ರಯತ್ನಿಸುತ್ತಿರುವುದನ್ನು ಉತ್ತಮವಾಗಿ ಕಳುಹಿಸಲು ಪ್ರಯತ್ನಿಸುತ್ತದೆ, ಇದು ಅನಿರೀಕ್ಷಿತ ಫಲಿತಾಂಶಗಳಿಗೆ ಕಾರಣವಾಗಬಹುದು. ಆದ್ದರಿಂದ ಅದನ್ನು ಮಾಡಬೇಡಿ!

**ಖಾಲಿ/ ಎಂಪ್ಟಿ ಎಲಿಮೆಂಟ್ಸ್**

ಕೆಲವು ಎಲಿಮೆಂಟ್ಸ್ ಗಳಿಗೆ ಯಾವುದೇ ವಿಷಯವಿಲ್ಲ ಮತ್ತು ಅವುಗಳನ್ನು ಎಂಪ್ಟಿ ಎಲಿಮೆಂಟ್ಸ್ ಎಂದು ಕರೆಯಲಾಗುತ್ತದೆ. ನಮ್ಮ HTML ಪುಟದಲ್ಲಿ ನಾವು ಈಗಾಗಲೇ ಹೊಂದಿರುವ <img> ಎಲಿಮೆಂಟ್ಸ್ ನ್ನು ತೆಗೆದುಕೊಳ್ಳಿ:

<img src=”images/firefox-icon.png” alt=”My test image”>

ಇದು ಎರಡು attributesನ್ನು ಹೊಂದಿದೆ, ಆದರೆ ಯಾವುದೇ ಮುಕ್ತಾಯ </ img> ಟ್ಯಾಗ್ ಇಲ್ಲ ಮತ್ತು inner content ಇಲ್ಲ. ಚಿತ್ರದ element ಅದರ ಮೇಲೆ ಪರಿಣಾಮ ಬೀರಲು ವಿಷಯವನ್ನು ಸುತ್ತುವುದಿಲ್ಲ ಎಂಬುದು ಇದಕ್ಕೆ ಕಾರಣ. ಚಿತ್ರವು ಗೋಚರಿಸುವ ಸ್ಥಳದಲ್ಲಿ HTML ಪುಟದಲ್ಲಿ ಎಂಬೆಡ್ ಮಾಡುವುದು ಇದರ ಉದ್ದೇಶ.

**HTML ಡಾಕ್ಯುಮೆಂಟ್‌ನ ಅನಾಟಮಿ**

ಅದು ಪ್ರತ್ಯೇಕ HTML ಎಲಿಮೆಂಟ್ ಗಳ ಮೂಲಭೂತ ಎಲಿಮೆಂಟ್ ನ್ನು ಸುತ್ತುತ್ತದೆ, ಆದರೆ ಅವುಗಳು ತಮ್ಮದೇ ಆದ ಮೇಲೆ ಸೂಕ್ತವಲ್ಲ. ಸಂಪೂರ್ಣ HTML ಪುಟವನ್ನು ರೂಪಿಸಲು ಪ್ರತ್ಯೇಕ ಎಲಿಮೆಂಟ್ ನ್ನು ಹೇಗೆ ಸಂಯೋಜಿಸಲಾಗಿದೆ ಎಂಬುದನ್ನು ಈಗ ನಾವು ನೋಡೋಣ.

ನಮ್ಮ index.html ಉದಾಹರಣೆಯಲ್ಲಿ ನಾವು ಹಾಕಿದ ಕೋಡ್ ಅನ್ನು ಮತ್ತೆ ಭೇಟಿ ಮಾಡೋಣ (ಫೈಲ್‌ಗಳ ಲೇಖನದೊಂದಿಗೆ ನಾವು ಮೊದಲು ಭೇಟಿಯಾದರು):

<!DOCTYPE html>

<html>

<head>

<meta charset=”utf-8">

<title>My test page</title>

</head>

<body>

<img src=”images/firefox-icon.png” alt=”My test image”>

</body>

</html>

ಇಲ್ಲಿ, ನಾವು ಈ ಕೆಳಗಿನವುಗಳನ್ನು ಹೊಂದಿದ್ದೇವೆ:

-   <! DOCTYPE html> — ಡಾಕ್ಟೈಪ್. ಇದು ಅಗತ್ಯವಾದ ಮುನ್ನುಡಿಯಾಗಿದೆ. ಸಮಯದ ಮಿಸ್ಟ್‌ಗಳಲ್ಲಿ, HTML ಚಿಕ್ಕವನಾಗಿದ್ದಾಗ (ಸುಮಾರು 1991/92 ರ ಸುಮಾರಿಗೆ), ಡಾಕ್ಟೈಪ್‌ಗಳನ್ನು ಉತ್ತಮ HTML ಎಂದು ಪರಿಗಣಿಸಲು HTML ಪುಟವು ಅನುಸರಿಸಬೇಕಾದ ನಿಯಮಗಳ ಗುಂಪಿನ ಲಿಂಕ್‌ಗಳಾಗಿ ಕಾರ್ಯನಿರ್ವಹಿಸಲು ಉದ್ದೇಶಿಸಲಾಗಿತ್ತು, ಇದರರ್ಥ ಸ್ವಯಂಚಾಲಿತ ದೋಷ ಪರಿಶೀಲನೆ ಮತ್ತು ಇತರ ಉಪಯುಕ್ತ ವಸ್ತುಗಳು. ಆದಾಗ್ಯೂ, ಈ ದಿನಗಳಲ್ಲಿ, ಅವರು ಹೆಚ್ಚಿನದನ್ನು ಮಾಡುವುದಿಲ್ಲ ಮತ್ತು ನಿಮ್ಮ ಡಾಕ್ಯುಮೆಂಟ್ ಸರಿಯಾಗಿ ವರ್ತಿಸುತ್ತಿದೆಯೆ ಎಂದು ಖಚಿತಪಡಿಸಿಕೊಳ್ಳಲು ಮೂಲತಃ ಅಗತ್ಯವಾಗಿರುತ್ತದೆ. ಸದ್ಯಕ್ಕೆ ನೀವು ತಿಳಿದುಕೊಳ್ಳಬೇಕಾದದ್ದು ಅಷ್ಟೆ.
-   <html> </html> — <html> element. ಈ element ಇಡೀ ಪುಟದಲ್ಲಿನ ಎಲ್ಲಾ ವಿಷಯವನ್ನು ಸುತ್ತುತ್ತದೆ/wrap ಮತ್ತು ಇದನ್ನು ಕೆಲವೊಮ್ಮೆ root element ಎಂದು ಕರೆಯಲಾಗುತ್ತದೆ.
-   <head> </head> — <head> element. ಈ element ನಿಮ್ಮ ಪುಟದ ವೀಕ್ಷಕರಿಗೆ ನೀವು ತೋರಿಸುತ್ತಿರುವ ವಿಷಯವಲ್ಲದ HTML ಪುಟದಲ್ಲಿ ನೀವು ಸೇರಿಸಲು ಬಯಸುವ ಎಲ್ಲಾ ವಿಷಯಗಳಿಗೆ ಧಾರಕವಾಗಿ ಕಾರ್ಯನಿರ್ವಹಿಸುತ್ತದೆ. ಕೀವರ್ಡ್‌ಗಳು ಮತ್ತು ಹುಡುಕಾಟ ಫಲಿತಾಂಶಗಳಲ್ಲಿ ನೀವು ಕಾಣಿಸಿಕೊಳ್ಳಲು ಬಯಸುವ ಪುಟ ವಿವರಣೆ, ನಮ್ಮ ವಿಷಯವನ್ನು ವಿನ್ಯಾಸಗೊಳಿಸಲು ಸಿಎಸ್ಎಸ್, ಅಕ್ಷರ ಸೆಟ್ ಘೋಷಣೆಗಳು ಮತ್ತು ಹೆಚ್ಚಿನವುಗಳನ್ನು ಇದು ಒಳಗೊಂಡಿದೆ.
-   <meta charset = “utf-8”> — ಈ element ನಿಮ್ಮ ಡಾಕ್ಯುಮೆಂಟ್ ಯುಟಿಎಫ್ -8 ಗೆ ಬಳಸಬೇಕಾದ ಅಕ್ಷರವನ್ನು ಹೊಂದಿಸುತ್ತದೆ, ಇದು ಬಹುಪಾಲು ಲಿಖಿತ ಭಾಷೆಗಳ ಹೆಚ್ಚಿನ ಅಕ್ಷರಗಳನ್ನು ಒಳಗೊಂಡಿದೆ. ಮೂಲಭೂತವಾಗಿ, ಇದೀಗ ನೀವು ಅದರ ಮೇಲೆ ಹಾಕಬಹುದಾದ ಯಾವುದೇ text ವಿಷಯವನ್ನು ಇದು ನಿಭಾಯಿಸುತ್ತದೆ. ಇದನ್ನು ಹೊಂದಿಸದಿರಲು ಯಾವುದೇ ಕಾರಣವಿಲ್ಲ ಮತ್ತು ನಂತರದ ಕೆಲವು ಸಮಸ್ಯೆಗಳನ್ನು ತಪ್ಪಿಸಲು ಇದು ಸಹಾಯ ಮಾಡುತ್ತದೆ.
-   <title> </ title> — <title> element. ಇದು ನಿಮ್ಮ ಪುಟದ ಶೀರ್ಷಿಕೆಯನ್ನು ಹೊಂದಿಸುತ್ತದೆ, ಇದು ಪುಟವನ್ನು ಲೋಡ್ ಮಾಡಲಾದ ಬ್ರೌಸರ್ ಟ್ಯಾಬ್‌ನಲ್ಲಿ ಕಾಣಿಸಿಕೊಳ್ಳುವ ಶೀರ್ಷಿಕೆಯಾಗಿದೆ.ನೀವು ಪುಟವನ್ನು ಬುಕ್‌ಮಾರ್ಕ್ ಮಾಡಿದಾಗ / ಇಷ್ಟಪಟ್ಟಾಗ ಅದನ್ನು ವಿವರಿಸಲು ಸಹ ಇದನ್ನು ಬಳಸಲಾಗುತ್ತದೆ.
-   <body> </body> — <body> element. ವೆಬ್ ಬಳಕೆದಾರರು ನಿಮ್ಮ ಪುಟಕ್ಕೆ ಭೇಟಿ ನೀಡಿದಾಗ,text, ಚಿತ್ರಗಳು, ವೀಡಿಯೊಗಳು, ಆಟಗಳು, ನುಡಿಸಬಲ್ಲ ಆಡಿಯೊ ಟ್ರ್ಯಾಕ್‌ಗಳು ಅಥವಾ ಇನ್ನಾವುದಾದರೂ ನೀವು ಅವರಿಗೆ ತೋರಿಸಲು ಬಯಸುವ ಎಲ್ಲಾ ವಿಷಯವನ್ನು ಇದು ಒಳಗೊಂಡಿದೆ.

**Images/ಚಿತ್ರಗಳು**

ನಮ್ಮ ಗಮನವನ್ನು ಮತ್ತೆ <img> element ತಿರುಗಿಸೋಣ:

<img src=”images/firefox-icon.png” alt=”My test image”>

ನಾವು ಮೊದಲೇ ಹೇಳಿದಂತೆ, ಅದು ಗೋಚರಿಸುವ ಸ್ಥಾನದಲ್ಲಿ ಚಿತ್ರವನ್ನು ನಮ್ಮ ಪುಟಕ್ಕೆ ಎಂಬೆಡ್ attribute ಮೂಲಕ ಮಾಡುತ್ತದೆ.

ನಾವು alt (ಪರ್ಯಾಯ) attributeನ್ನೂ ಸೇರಿಸಿದ್ದೇವೆ. ಈ attributeಲ್ಲಿ, ಚಿತ್ರವನ್ನು ನೋಡಲಾಗದ ಬಳಕೆದಾರರಿಗಾಗಿ ನೀವು ವಿವರಣಾತ್ಮಕ textನ್ನು ನಿರ್ದಿಷ್ಟಪಡಿಸುತ್ತೀರಿ, ಬಹುಶಃ ಈ ಕೆಳಗಿನ ಕಾರಣಗಳಿಂದಾಗಿ:

1.  ಅವರು ದೃಷ್ಟಿಹೀನರಾಗಿದ್ದಾರೆ. ಗಮನಾರ್ಹ ದೃಷ್ಟಿ ದೋಷ ಹೊಂದಿರುವ ಬಳಕೆದಾರರು ಪರದೆ ಪಠ್ಯವನ್ನು ಓದಲು ಸ್ಕ್ರೀನ್ ರೀಡರ್ಸ್ ಎಂಬ ಸಾಧನಗಳನ್ನು ಬಳಸುತ್ತಾರೆ.
2.  ಚಿತ್ರವು ಪ್ರದರ್ಶಿಸದಿರಲು ಏನೋ ತಪ್ಪಾಗಿದೆ. ಉದಾಹರಣೆಗೆ, ನಿಮ್ಮ src attributeನ ಮಾರ್ಗವನ್ನು ತಪ್ಪಾಗಿ ಮಾಡಲು ಉದ್ದೇಶಪೂರ್ವಕವಾಗಿ ಬದಲಾಯಿಸಲು ಪ್ರಯತ್ನಿಸಿ. ನೀವು ಪುಟವನ್ನು ಉಳಿಸಿ ಮತ್ತು ಮರುಲೋಡ್ ಮಾಡಿದರೆ, ಚಿತ್ರದ ಸ್ಥಳದಲ್ಲಿ ನೀವು ಈ ರೀತಿಯದನ್ನು ನೋಡಬೇಕು:

ಆಲ್ಟ್ text ಕೀವರ್ಡ್ಗಳು “ವಿವರಣಾತ್ಮಕ ಪಠ್ಯ”. ನೀವು ಬರೆಯುವ ಆಲ್ಟ್ text ಚಿತ್ರವು ಏನನ್ನು ತಿಳಿಸುತ್ತದೆ ಎಂಬುದರ ಬಗ್ಗೆ ಉತ್ತಮ ಆಲೋಚನೆಯನ್ನು ಹೊಂದಲು ಓದುಗರಿಗೆ ಸಾಕಷ್ಟು ಮಾಹಿತಿಯನ್ನು ಒದಗಿಸಬೇಕು. ಈ ಉದಾಹರಣೆಯಲ್ಲಿ, ನಮ್ಮ ಪ್ರಸ್ತುತ “ನನ್ನ ಪರೀಕ್ಷಾ ಚಿತ್ರ” ಪಠ್ಯವು ಉತ್ತಮವಾಗಿಲ್ಲ. ನಮ್ಮ ಫೈರ್‌ಫಾಕ್ಸ್ ಲೋಗೊ ಉತ್ತಮ ಪರ್ಯಾಯವೆಂದರೆ “ಫೈರ್‌ಫಾಕ್ಸ್ ಲೋಗೊ: ಭೂಮಿಯ ಸುತ್ತ ಜ್ವಲಂತ ನರಿ.”

**ಮಾರ್ಕಿಂಗ್ ಅಪ್ ಟೆಕ್ಸ್ಟ್ /ಪಠ್ಯವನ್ನು ಗುರುತಿಸುವುದು**

ಈ ವಿಭಾಗವು ಟೆಕ್ಸ್ಟ್ ನ್ನು ಗುರುತಿಸಲು ನೀವು ಬಳಸುವ ಕೆಲವು ಅಗತ್ಯ HTML elementಗಳನ್ನು ಒಳಗೊಂಡಿದೆ.

**Headings/ಶೀರ್ಷಿಕೆಗಳು**

ನಿಮ್ಮ ವಿಷಯದ ಕೆಲವು ಭಾಗಗಳು ಶೀರ್ಷಿಕೆಗಳು — ಅಥವಾ ಉಪಶೀರ್ಷಿಕೆಗಳು ಎಂದು ನಿರ್ದಿಷ್ಟಪಡಿಸಲು ಶೀರ್ಷಿಕೆ elementಗಳು ನಿಮಗೆ ಅನುಮತಿಸುತ್ತದೆ. ಪುಸ್ತಕವು ಮುಖ್ಯ ಶೀರ್ಷಿಕೆ, ಅಧ್ಯಾಯದ ಶೀರ್ಷಿಕೆಗಳು ಮತ್ತು ಉಪಶೀರ್ಷಿಕೆಗಳನ್ನು ಹೊಂದಿರುವ ರೀತಿಯಲ್ಲಿಯೇ, ಒಂದು HTML ಡಾಕ್ಯುಮೆಂಟ್ ಕೂಡ ಮಾಡಬಹುದು. HTML 6 ಶೀರ್ಷಿಕೆ ಮಟ್ಟವನ್ನು ಹೊಂದಿದೆ, <h1> — <h6>, ಆದರೂ ನೀವು ಸಾಮಾನ್ಯವಾಗಿ 3 ರಿಂದ 4 ಅನ್ನು ಮಾತ್ರ ಬಳಸುತ್ತೀರಿ:

<h1>My main title</h1>

<h2>My top level heading</h2>

<h3>My subheading</h3>

<h4>My sub-subheading</h4>

ಈಗ ನಿಮ್ಮ <img> element ಮೇಲಿರುವ ನಿಮ್ಮ HTML ಪುಟಕ್ಕೆ ಸೂಕ್ತವಾದ ಶೀರ್ಷಿಕೆಯನ್ನು ಸೇರಿಸಲು ಪ್ರಯತ್ನಿಸಿ.

**Paragraphs/ಪ್ಯಾರಾಗಳು**

ಮೇಲೆ ವಿವರಿಸಿದಂತೆ, <p> elementಗಳು text ಪ್ಯಾರಾಗಳನ್ನು ಒಳಗೊಂಡಿರುತ್ತವೆ; ಸಾಮಾನ್ಯ text content ನ್ನು ಗುರುತಿಸುವಾಗ ನೀವು ಇದನ್ನು ಹೆಚ್ಚಾಗಿ ಬಳಸುತ್ತೀರಿ:

<p>This is a single paragraph</p>

ನಿಮ್ಮ ಮಾದರಿ textನ್ನು (ನಿಮ್ಮ ವೆಬ್‌ಸೈಟ್ ಹೇಗಿರಬೇಕು?) ಒಂದು ಅಥವಾ ಕೆಲವು ಪ್ಯಾರಾಗಳಲ್ಲಿ ಸೇರಿಸಿ, ಅದನ್ನು ನಿಮ್ಮ <img> element ನೇರವಾಗಿ ಇರಿಸಿ.

**Lists/ಪಟ್ಟಿಗಳು**

ವೆಬ್‌ನ ಬಹಳಷ್ಟು ವಿಷಯವು lists ಮತ್ತು HTML ಇವುಗಳಿಗೆ ವಿಶೇಷ elementಗಳನ್ನು ಹೊಂದಿದೆ. ಪಟ್ಟಿಗಳನ್ನು ಗುರುತಿಸುವುದು ಯಾವಾಗಲೂ ಕನಿಷ್ಠ 2 ಅಂಶಗಳನ್ನು ಹೊಂದಿರುತ್ತದೆ. ಸಾಮಾನ್ಯ ಪಟ್ಟಿ ಪ್ರಕಾರಗಳನ್ನು ಆದೇಶಿಸಲಾಗಿದೆ ordered ಮತ್ತು unordered ಪಟ್ಟಿಗಳು:

1.  **Unordered lists:** ಶಾಪಿಂಗ್ ಪಟ್ಟಿಯಂತಹ ಐಟಂಗಳ ಕ್ರಮವು ಅಪ್ರಸ್ತುತವಾಗುವ ಪಟ್ಟಿಗಳಿಗಾಗಿ ಆದೇಶವಿಲ್ಲದ ಪಟ್ಟಿಗಳು. ಇವುಗಳನ್ನು <ul> elementಲ್ಲಿ wrap/ಸುತ್ತಿಡಲಾಗುತ್ತದೆ.
2.  **ordered lists:** ಪಾಕವಿಧಾನದಂತಹ ವಸ್ತುಗಳ ಕ್ರಮವು ಮುಖ್ಯವಾದ ಪಟ್ಟಿಗಳಿಗಾಗಿ ಆದೇಶಿಸಲಾದ ಪಟ್ಟಿಗಳು. ಇವುಗಳನ್ನು <ol> elementಲ್ಲಿ ಸುತ್ತಿಡಲಾಗುತ್ತದೆ.

ಪಟ್ಟಿಗಳೊಳಗಿನ ಪ್ರತಿಯೊಂದು ಐಟಂ ಅನ್ನು <li> (ಪಟ್ಟಿ ಐಟಂ) ಎಲಿಮೆಂಟ್ಲ್ಲಿ ಇರಿಸಲಾಗುತ್ತದೆ.

ಉದಾಹರಣೆಗೆ, ನಾವು ಈ ಕೆಳಗಿನ ಪ್ಯಾರಾಗ್ರಾಫ್ ತುಣುಕಿನ ಭಾಗವನ್ನು ಪಟ್ಟಿಯನ್ನಾಗಿ ಮಾಡಲು ಬಯಸಿದರೆ

<p>At Mozilla, we’re a global community of technologists, thinkers, and builders working together … </p>

ನಾವು ಇದಕ್ಕೆ ಮಾರ್ಕ್ಅಪ್ ಅನ್ನು ಮಾರ್ಪಡಿಸಬಹುದು

<p>At Mozilla, we’re a global community of</p>

<ul> <li>technologists</li>

<li>thinkers</li>

<li>builders</li> </ul>

<p>working together … </p>

ನಿಮ್ಮ ಉದಾಹರಣೆ ಪುಟಕ್ಕೆ ಆದೇಶಿಸಿದ ಅಥವಾ ಕ್ರಮವಿಲ್ಲದ ಪಟ್ಟಿಯನ್ನು ಸೇರಿಸಲು ಪ್ರಯತ್ನಿಸಿ.

**ಲಿಂಕ್‌ಗಳು**

ಲಿಂಕ್‌ಗಳು ಬಹಳ ಮುಖ್ಯ — ಅವುಗಳು ವೆಬ್ ಅನ್ನು ವೆಬ್‌ನನ್ನಾಗಿ ಮಾಡುತ್ತದೆ! ಲಿಂಕ್ ಅನ್ನು ಸೇರಿಸಲು, ನಾವು ಸರಳ elementನ್ನು ಬಳಸಬೇಕಾಗಿದೆ — <a> — “a” “ಆಂಕರ್” ಗಾಗಿ ಕಿರು ರೂಪವಾಗಿದೆ. ನಿಮ್ಮ ಪ್ಯಾರಾಗ್ರಾಫ್‌ನಲ್ಲಿನ textನ್ನು ಲಿಂಕ್ ಆಗಿ ಮಾಡಲು, ಈ ಹಂತಗಳನ್ನು ಅನುಸರಿಸಿ:

1.  ಕೆಲವು ಪಠ್ಯವನ್ನು ಆರಿಸಿ. ನಾವು “ಮೊಜಿಲ್ಲಾ ಮ್ಯಾನಿಫೆಸ್ಟೋ” ಪಠ್ಯವನ್ನು ಆರಿಸಿದ್ದೇವೆ.
2.  ಕೆಳಗೆ ತೋರಿಸಿರುವಂತೆ ಪಠ್ಯವನ್ನು <a> ಅಂಶದಲ್ಲಿ ಕಟ್ಟಿಕೊಳ್ಳಿ:

<a>Mozilla Manifesto</a>

3.ಕೆಳಗೆ ತೋರಿಸಿರುವಂತೆ <a> ಅಂಶಕ್ಕೆ href ಗುಣಲಕ್ಷಣವನ್ನು ನೀಡಿ:

<a href=””>Mozilla Manifesto</a>

4.ಲಿಂಕ್ ಅನ್ನು ಲಿಂಕ್ ಮಾಡಲು ನೀವು ಬಯಸುವ ವೆಬ್ ವಿಳಾಸದೊಂದಿಗೆ ಈ ಗುಣಲಕ್ಷಣದ ಮೌಲ್ಯವನ್ನು ಭರ್ತಿ ಮಾಡಿ:

<a href=”https://www.mozilla.org/en-US/about/manifesto/">Mozilla Manifesto</a>

ವೆಬ್ ವಿಳಾಸದ ಆರಂಭದಲ್ಲಿ ಪ್ರೋಟೋಕಾಲ್ ಎಂದು ಕರೆಯಲ್ಪಡುವ https: // ಅಥವಾ http: // ಭಾಗವನ್ನು ನೀವು ಬಿಟ್ಟುಬಿಟ್ಟರೆ ನೀವು ಅನಿರೀಕ್ಷಿತ ಫಲಿತಾಂಶಗಳನ್ನು ಪಡೆಯಬಹುದು. ಲಿಂಕ್ ಮಾಡಿದ ನಂತರ, ನೀವು ಬಯಸಿದಲ್ಲಿ ಅದು ನಿಮಗೆ ಕಳುಹಿಸುತ್ತಿದೆ ಎಂದು ಖಚಿತಪಡಿಸಿಕೊಳ್ಳಲು ಅದನ್ನು ಕ್ಲಿಕ್ ಮಾಡಿ.

ನೀವು ಈಗಾಗಲೇ ಹಾಗೆ ಮಾಡದಿದ್ದರೆ ಈಗ ನಿಮ್ಮ ಪುಟಕ್ಕೆ ಲಿಂಕ್ ಸೇರಿಸಿ.

**ತೀರ್ಮಾನ**

ಈ ಲೇಖನದ ಎಲ್ಲಾ ಸೂಚನೆಗಳನ್ನು ನೀವು ಅನುಸರಿಸಿದ್ದರೆ, ಕೆಳಗಿನ ಪುಟದಂತೆ ಕಾಣುವ ಪುಟದೊಂದಿಗೆ ನೀವು ಕೊನೆಗೊಳ್ಳಬೇಕು (ನೀವು ಇದನ್ನು ಸಹ ಇಲ್ಲಿ ವೀಕ್ಷಿಸಬಹುದು):

![Image for post](https://miro.medium.com/max/52/0*ZaJD_ccpBICCsir3?q=20)

Article by Shruthi K V

MicroDegree is an edtech platform for learning Emerging Technologies such as Full-Stack Development, Data Science, Machine Learning using vernacular at an affordable price. For more details reach out to hello@microdegree.work

🚀 For Course Certification : [https://bit.ly/3gt2nY7](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqblAzcGQxZlRtSmdYZlppbDNUd2t0MFNSanV1QXxBQ3Jtc0tuS2VjaXpMd1hFS1I5NEFuMkxkYThlZE9MZkVzNGFmTXYxTTRtZjBsX0lkSTU3MEpEdnpCTnI3MUp2QVpNdWc0LXBjNEpVWEVhMTBuajBEeXRiMnZSWnpFVDJHMTlCRk91bkNpR24ySGxUSzJUblNfUQ%3D%3D&q=https%3A%2F%2Fbit.ly%2F3gt2nY7)

👍 Youtube:: [https://bit.ly/3ajK4Cz](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqbDlUVFVtUVN1Wnl0Z3lpZ19aUVV5ZVU1SWQyQXxBQ3Jtc0tuamNVOWJCVkdsNmwzcEF2VG1XS0cwYmZWekJVbFp2enBldkg1WUEzUm1iSkZuV0ZzbGduSG8tSXlRM1N1bzRtR1BCMGN2cTJMekJSS0xzVE9pdFBrd2hpNUV5SDQ5dl9sSFFYbERzQ1NNdU5CWWU4WQ%3D%3D&q=https%3A%2F%2Fbit.ly%2F3ajK4Cz)

Website : [https://microdegree.work](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqbjR2M3JJekdSZTZlTVFCNkt5RFBTc1JNMlhpUXxBQ3Jtc0tuZHhRdjZtQW9ubmliWXAxSVNfMm5UemNrS2RMd1hDMmtIdEdGcmlFZmpkTDRkV1JFbkl3Wng1b2NRSXZJeWVlMjFGWmRpWmJSUU5jTGZmMFA0NTMxRUJtTnBlVlNESUdDYlA1QU4tcUdzZ1gwZHFUWQ%3D%3D&q=https%3A%2F%2Fmicrodegree.work)

LinkedIn : [https://www.linkedin.com/company/micr](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqa1Z1SEw5M182a2I3ZC1BN25WeFdYYVNaRWkzQXxBQ3Jtc0tsTmlGQkN5RExFekhvWWFjVHJEZUZadVZVNW5NTURjYkxaSWlVTzFJaVU0aUJ3Q1Y1QXZaRU5sbEJFaVpiOUp6a3V4a3dZczVlSVA4SzVvYU1Jc3A3SEVUMkROUEpNeFFSNkxrbldZOVhTQTBUQWdFbw%3D%3D&q=https%3A%2F%2Fwww.linkedin.com%2Fcompany%2Fmicr)...

Facebook : [https://www.facebook.com/microdegree](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqa3BNeV9oRnNsVmdiMW1malJ4M3M2REVXUVItUXxBQ3Jtc0tsN0V6MXIxOXRCSU9DMDVBQm0wemEyMnFWMWRNQVRNNlNxX2ZwOHdQLWRUWVQ1SnBSR3JFLUFnLV9VS2FYdk9QQ0x5MjZZOEMyV2JkV2o2emNVMHhZVEZUbDRKdTBoVnBXS3FGNERiZkN3aFNXOF9Xbw%3D%3D&q=https%3A%2F%2Fwww.facebook.com%2Fmicrodegree)

Instagram : [https://www.instagram.com/micro.degree](https://www.youtube.com/redirect?event=video_description&v=fEfKw_FGRjM&redir_token=QUFFLUhqbU82YjFKOFBrMXZ4QkRrWWtlbTlzV1VvU1g1QXxBQ3Jtc0trYndfRGt1cUtVS3ZUaFRkVEJtSUd4M1VJTndfR2s1WDQ0Y3Axd0dXdzN1eVRNZHF2VEo5MFhyZkkxRmVXcXJZMUN0X1dXYTZsY1RyNS11OVJWWG0zd0ZKX1EzcXJMSFU4Tnd2QzF6dUJYLTdrZW0zaw%3D%3D&q=https%3A%2F%2Fwww.instagram.com%2Fmicro.degree)