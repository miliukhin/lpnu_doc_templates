---
pdf-engine: xelatex
mainfont: "Linux Libertine"
monofont: "Iosevka Fixed Curly"
fontsize: 12pt
header-includes:
- \input{$UNI/.templates/settings/preamble.tex}
- \input{$UNI/.templates/settings/minted_settings.tex}
- \renewcommand\Variant{VARIANT}
- \newcommand\Date{DAY.MONTH.\the\year}
- \newcommand\Type{TYPE}
- \Work{DISCIPLINE}
- \newcommand\Number{NUMBER}
- \newcommand\Topic{TOPIC}
- \usepackage{etoolbox}
- \newtoggle{Report}
- \toggletrue{Report}
- \newtoggle{ShowVar}
- \togglefalse{ShowVar}
- \renewcommand\Department{САПР}
- \newcommand\Class{студент групи \Group}
- \newcommand\Author{\Lname~\Initials}
- \newcommand\Position{POSITION}
---

\input{$UNI/.templates/parts/titlepage.tex}
<++>

# Індивідуальне завдання

<++>

# Етапи розв'язку

BODY

\clearpage

# Висновок

<++>

# Відповіді на контрольні запитання

<++>
