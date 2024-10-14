---
pdf-engine: xelatex
header-includes:
- \input{$UNI/.templates/settings/preamble.tex}
- \input{$UNI/.templates/settings/minted_settings.tex}
- \newcommand\Type{TYPE}
- \Work{DISCIPLINE}
- \renewcommand\Variant{VARIANT}
- \newcommand\Date{<++>.\the\month.\the\year}
- \newcommand\Number{NUMBER}
- \newcommand\Topic{<++>}
---

\input{$UNI/.templates/parts/header.tex}
<++>

# Індивідуальне завдання

<++>

# Етапи розв'язку

## Завдання 1
\inputminted{c}{t1/t1.ino}

## Завдання 2
\inputminted{c}{t2/t2.ino}

## Завдання 3
\inputminted{c}{t3/t3.ino}

# Висновок

<++>

# Відповіді на контрольні запитання
\begin{itemize}
	\question <++>
	\answer <++>

	\question <++>
	\answer <++>

	\question <++>
	\answer <++>

	\question <++>
	\answer <++>

	\question <++>
	\answer <++>
\end{itemize}
