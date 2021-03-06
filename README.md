# PlotlyJS

[![Join the chat at https://gitter.im/sglyon/PlotlyJS.jl](https://badges.gitter.im/sglyon/PlotlyJS.jl.svg)](https://gitter.im/sglyon/PlotlyJS.jl?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[![Build Status](https://travis-ci.org/sglyon/PlotlyJS.jl.svg?branch=master)](https://travis-ci.org/sglyon/PlotlyJS.jl)

Julia interface to [plotly.js][_plotlyjs] visualization library.

This package constructs plotly graphics using all local resources. To interact or save graphics to the Plotly cloud, use the  [`Plotly`](https://github.com/plotly/Plotly.jl) package.

Check out the [docs](http://juliaplots.org/PlotlyJS.jl/stable)!



[_plotlyjs]: https://plot.ly/javascript

## Installation

If you have issues building this package because of installation of the MbedTLS  package please see [this issue](https://github.com/sglyon/PlotlyJS.jl/issues/83).

### Jupyterlab

If you will be using this package from within Jupyterlab, please also install the plotly jupyterlab extension by running:


```sh
jupyter labextension install jupyterlab-plotly
```

See the [jupyterlab extension documentation](https://jupyterlab.readthedocs.io/en/stable/user/extensions.html) for more details.


