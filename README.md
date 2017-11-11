# code-for-DEA
#### Copyright (c) 2017 Wen-Chih Chen
This is a collection of codes for data envelopment analysis (DEA) computation based on [Julia](https://julialang.org/) programming language and [JuMP](https://github.com/JuliaOpt/JuMP.jl) modeling language, which is as fast as [AMPL](http://ampl.com) and faster than any other modeling tools such as [GAMS](http://www.gams.com) and [Pyomo](http://www.pyomo.org) (see [this](http://arxiv.org/pdf/1312.1431.pdf)).

#example.jl# is a simple JuMP code for the input-oriented CRS (CCR) model.

#basicDEAmodel.jl# is the  code for computing DEA models based on input- or output- orientation and different returns to scale.

#outlierDetection.jl# implements the model to detect efficient and inefficient outliers ([Chen and Johnson, 2010](https://doi.org/10.1016/j.cor.2009.06.010)).
