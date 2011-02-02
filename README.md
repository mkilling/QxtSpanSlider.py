# QxtSpanSlider.py
Span slider for PyQt ported from [libqxt](http://libqxt.bitbucket.org/doc):  
![Span slider](http://libqxt.bitbucket.org/doc/tip/images/qxtspanslider.png)

## Usage

    from QxtSpanSlider import QxtSpanSlider
    
    # ...
    
    slider = QxtSpanSlider(self.window)
    slider.setSpan(0, 100)
    slider.setLowerPosition(10)
    slider.setUpperPosition(20)
