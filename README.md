# isosigns

[![Static Badge](https://img.shields.io/badge/Version-v2-blue)](https://github.com/BenSt099/isosigns/releases/tag/v2)
[![Static Badge](https://img.shields.io/badge/Package-CTAN-blue)](https://www.ctan.org/pkg/isosafety)
![Static Badge](https://img.shields.io/badge/Size-%3C2%20MB-red)
![Static Badge](https://img.shields.io/badge/Maintained-Yes-success)

## Attention

The older version of this package was called "isosafety" and is no longer supported. Moreover, the versions of isosafety (v1.1 and v1.2) both contain bugs.

## Documentation

The documentation can be viewed [here](https://github.com/BenSt099/isosigns/blob/main/isosigns/doc/isosigns-docs.pdf).

## Known Issues

If Latex tells you that it does not find any pdf-files, please provide a full path to the package on your system via the `fullpath`-option:

```
                        % example path
\usepackage[ fullpath = /texlive/2024/texmf-dist/tex/latex/isosafety ]{isosafety}

\begin{document}

    \includegraphics[scale=1]{\Isosign{F001}}

\end{document}
```

## Issues

In case of an issue, please provide a detailed description [here](https://github.com/BenSt099/isosafety/issues).

## License

This project is licensed under the [The LaTeX Project Public License 1.3c](https://www.ctan.org/license/lppl1.3c)
