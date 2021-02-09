# john-snow
Spatial analysis playground using data related to data for the [1854 cholera outbreak in Soho](https://en.wikipedia.org/wiki/1854_Broad_Street_cholera_outbreak).

## data
Data are from several sources:
- `data/csds` contains data prepared by [Center for Spatial Data Science](https://geodacenter.github.io/data-and-lab//snow/).
- `data/dani` contains data prepared by [Dani Arribas-Bel](https://bitbucket.org/darribas/reproducible_john_snow/src/master/)

Both of the data sets above are based in some way on data prepared by [Robin Wilson](http://blog.rtwilson.com/john-snows-cholera-data-in-more-formats/)

## code

- [Relations.ipynb](https://github.com/jamesdamillington/john-snow/blob/main/code/python/Relations.ipynb) is a python notebook using the [shapely package](https://pypi.org/project/Shapely/) exploring some examples of spatial relations, specifically: distances (between points); within and contains (points and polygons); overlaps (of polygons); buffers (around points; technically an operation, but it makes sense to consider them here)
- [Opererations.ipynb](https://github.com/jamesdamillington/john-snow/blob/main/code/python/Operations.ipynb) is a python notebook using the [shapely package](https://pypi.org/project/Shapely/) exploring some examples of spatial operations, specifically: differences (between polygons); intersections (of polygons); unions (of polygons)
- [Voronoi.ipynb](https://github.com/jamesdamillington/john-snow/blob/main/code/python/Voronoi.ipynb) is a python notebook providing overview of Voronoi Diagrams (Thiessen Polygons) using [pysal](https://pysal.org/libpysal)
- [Arribas-Bel_etal_2017.ipynb](/code/python/Arribas-Bel_etal_2017.ipynb) re-implements python code from [Arribas-Bel _et al._ (2017)](http://doi.org/10.1007/978-3-319-50590-9_17) for more recent versions of packages


### References

Johson, S. (2006) _The Ghost Map_ London: Penguin [link](https://en.wikipedia.org/wiki/The_Ghost_Map)
