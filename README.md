# LaTeXt
Python package for converting LaTeX to text which can be read by text to speech programs.

Currently just a pile of substitutions of symbols and things surrounded by $'s.
Documation coming eventually.

### Installation
Install with pip:
```
pip install latext
```

### Usage
Example
```
>>>from latext import latex_to_text
>>>text = '$10^2\pm3$'
>>>print(latex_to_text(text))
10 to the power of 2 plus or minus 3
```


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
