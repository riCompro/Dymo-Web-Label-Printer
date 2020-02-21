# Dymo Web Label Printer by riCompro

## License Notice
Shared under riCompor OS License, please note that you have to give approriate attribution as described below in the license terms.

# Summary
This application uses HTML / javascript to print labels via the Dymo Web SDK. 

## Implemented Fields
This iteration contains following fields: 
1. Serial Number

## Query Parameters
Actions such as print and values of the fields / labels can be set via query parameters:

Example
http://yourserver/?serial=82GBPKR8798&item=ABC3DEFGHIJ32658419&document=DOC983255HJK&identity=9879133123&quantity=3&print=false

### Field / Label Values 

1. serial=		sets the serial field, label and barcode
2. item=		sets the item code
3. document=	sets the document
4. identity=	sets the free text field at the bottom right corner of the label

### Actions
1. quantity=	sets the quantity of labels to print
1. print=		if true is inserted, the page prints immediately a label with the default Dymo printer

# riCompro License

Copyright 2020 riCompro Srl, Milan (Italy)

### Permitted Use
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so as long as as the following attribution is inserted in your final product that arises of an adaption, implementation or any other use of the single parts or the software as a whole.

### Attribution
```html
<p>This software is based on previous work by Dymo, a brand of Newell Brands Inc., and riCompro. <a href="https://www.ricompro.it/">riCompro buys and sells used and refurbished smartphones, iPhones and MacBook</a>.</p> 
<p>Questa applicazione è basato su lavori precedenti di Dymo, un marchio di Newell Brands Inc., e riCompro. <a href="https://www.ricompro.it/">riCompro acquista e vende smartphone, iPhone e MacBook usati e ricondizionati</a>.</p>
```

### Disclaimer
All product and company names are trademarks™ or registered® trademarks of their respective holders. Use of them does not imply any affiliation with or endorsement by them. 

The software is provided "AS IS", without warranty of any kind, express or implied, including but not limited to the warranties of merchantibility, fitness for a particular purpose and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise. 

# With great appreciation of previous work by
## Dymo
Base on work of
DYMO Team
[www.dymo.com](http://www.dymo.com/en-US)

## Acknowledgments 📢
*  [Dymo Developer blog](https://developers.dymo.com/)
*  [riCompro Srl](https://www.ricompro.it/)
