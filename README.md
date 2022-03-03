#	SHA3.jl
[![CI status](https://github.com/Heptazhou/sha3.jl/actions/workflows/CI.yml/badge.svg)](https://github.com/Heptazhou/sha3.jl/actions/workflows/CI.yml)
[![codecov.io](https://codecov.io/gh/Heptazhou/sha3.jl/branch/master/graph/badge.svg)](https://app.codecov.io/gh/Heptazhou/sha3.jl)
<sup>*on master*</sup>

*****
##	Usage
```julia
julia> ]add https://github.com/Heptazhou/sha3.jl#stable

julia> using SHA3
julia> hash = ""          |> sha3_512 |> bytes2hex  # a69f73cca23a9ac5...
julia> hash = 'a'^71      |> sha3_512 |> bytes2hex  # 070faf98d2a8fddf...
julia> hash = read($file) |> sha3_512 |> bytes2hex
```

