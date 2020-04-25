# basicfractalsvg
basicfractalsvg parses BASIC programs to generate SVG images of fractals. It relies on `parslet` and `victor` libraries of ruby to generate the BASIC parser and to build the SVG images, respectively. 

basicfractalsvg can currently parse some of the BASIC programs (e.g., ARCHI, BROWNL, HENON) listed in the book "Fractals: Endlessly Repeated Geometrical Figures" by Hans Lauwerier (Princeton University Press, 1991).


## Use

```sh
basicfractalsvg BROWNL BROWNL.svg 500
```

reads BASIC code from `BROWNL` file to generate `BROWNL.svg` image after applying a scaling of `500` units. 
