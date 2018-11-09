---
title: MFC Overview
author: Brandon Behar
geometry: margin=1in
---

# CDC class primitives
- Rectangle
```
    pDC->Rectangle(int x1, int y1, int x2, int y2);
```
- Ellipse
```
    pDC->Ellipse(int x1, int y1, int x2, int y2);
```
- Rounded Rectangle
```
    pDC->RoundedRect(int x1, int y1, int x2, int y2, int x3, int y3);
```
- Line
```
    pDC->MoveTo(x, y); //Move pen to point
    pDC->LineTo(x, y); //Draw line from point to location
```
- Pie
```
    pDC->Pie(int x1, int y1, int x2, int y2, int x3, int y3, int x4, int y4);
```
- Arc
```
    pDC->Arc(int x1, int y1, int x2, int y2, int x3, int y3, int x4, int y4);
```
- Chord
```
    pDC->Chord(int x1, int y1, int x2, int y2, int x3, int y3, int x4, int y4);
```

# Dialog Boxes
- DDX: Dialog Data Exchange
- DDV: Dialog Data Validation


