[![Build Status](https://travis-ci.org/eweitz/ideogram.svg?branch=master)](https://travis-ci.org/eweitz/ideogram)

# ideogram
Chromosome visualization with D3.js

Examples: http://eweitz.github.io/ideogram/

# Installation

```
$ cd <your local web server document root>
$ git clone https://github.com/eweitz/ideogram.git
```

Then go to [http://localhost/ideogram/examples](http://localhost/ideogram/examples).

# Usage
```html
<head>
    <link type="text/css" rel="stylesheet" href="src/css/ideogram.css">
    <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/d3/3.5.17/d3.min.js"></script>
    <script type="text/javascript" src="src/js/ideogram.js"></script>
    <script type="text/javascript" src="data/bands/native/ideogram_9606_GCF_000001305.14_850_V1.js"></script>
</head>
<body>
    <script type="text/javascript">
        var ideogram = new Ideogram({
            organism: "human",
            annotations: [{
                "name": "BRCA1",
                "chr": "17",
                "start": 43044294,
                "stop": 43125482
            }]
        });
  </script>
</body>
```
