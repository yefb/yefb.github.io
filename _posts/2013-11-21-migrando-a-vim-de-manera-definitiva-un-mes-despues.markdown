---
layout: post
title: "Migrando a Vim de manera definitiva - Un mes después"
date: 2013-11-11 21:10
comments: true
categories: vim, colemak
published: true
---

Pues realmente, ¿Qué les puedo decir colegas?

He migrado a Vim hace un mes y medio, como lo mencioné en mi anterior atículo, y si bien he tenido algún que otro altibajo, nada ha sido tan grave como para desistir de mi objetivo.
He terminado de leer el libro [Practical Vim](http://pragprog.com/book/dnvim/practical-vim), y lo empecé a releer... sí, releer, porque es jodidamente bueno (Gracias [Drew](http://drewneil.com/)!).
El libro me enseñó muchas cosas, entre otras, a pensar como un vimmer, y a entender la famosa frase ["Your problem with Vim is that you don't grok Vi"](http://stackoverflow.com/a/1220118/1006075) (Hablaré de ello en otro artículo). Por favor, si quieren ser vimmers, lean el libro, Drew merece vender miles de copias más y volverse millonario, sin duda.

Un poco de información sobre mi Setup:

- Sigo usando pocos plug-ins, los cuales pueden ver en [mi .vimrc](https://github.com/yefb/dotfiles/blob/master/.vimrc). He agregado algunas cuantas configuraciones a medida que voy detectando las cosas que se me hacen útiles.
- [NERDTree](https://github.com/scrooloose/nerdtree), aunque es muy bueno, he considerado eliminarlo, pues no lo suelo usar mucho... pero tampoco me estoba :D.
- Desactivé las Arrow-Keys, para evitar usarlas en Modo Normal.
- Muy en contra de todos los "pronósticos", y en contra de la mayoría de Vimmers que conozco, prefiero [Command-T](https://github.com/wincent/Command-T) sobre [Ctrlp.vim](https://github.com/kien/ctrlp.vim), aunque el último tiene más features, quizás el hecho de que no funcione tan bien en mi PC personal haya afectado (En la oficina y con el mismo `.vimrc` funcionaba bien), el caso es que con **Command-T** estoy bastante satisfecho.
`CommandT`, `CommandTBuffer`, `CommandTJump`, etc... [son joyas](https://github.com/wincent/Command-T/blob/master/doc/command-t.txt), úsenlas (`Ctrlp.vim` [también tiene sus equivalentes](https://github.com/kien/ctrlp.vim/blob/master/doc/ctrlp.txt)).
- No he querido remapear mi `<leader>` key. Muchos suelen cambiar su `<leader>` a `,`, yo no. El default (Backslash `\`) no me parece malo, además la coma (`,`) ya tiene un uso en Vim por defecto, del cual suelo sacar provecho.
- [Vim Snipmate](https://github.com/garbas/vim-snipmate) es un muy buen plugin, he empezado a crear [mis propios Snippets](https://github.com/yefb/dotfiles/tree/master/.vim/snippets), al menos los que más usaba en Sublime Text.
- [Omni Completion](http://vimdoc.sourceforge.net/htmldoc/version7.html#new-omni-completion) en Vim es sencillamente genial cuando te acostumbras a usarlo.
- Estoy usando intensivamente los [Vim Text Objects](http://vimdoc.sourceforge.net/htmldoc/motion.html#object-select), es de las cosas que más me ha parecido útil, tanto que en dos días me acostumbré a usarlos en todo caso de uso posibles.
- Empecé a practicar mi Touch-Typing, actualmente estoy en un promedio de 48 WPM (Palabras por minuto) y quiero mejorar a mínimo 70 WPM. Para ello, cambié de keyboard Layout a [Colemak](http://colemak.com/) (Más sobre eso en otro artículo).
- Uso [Solarized](http://ethanschoonover.com/solarized), lo usaba en Sublime Text y en Terminator, lo tengo en Konsole, en Vim, en este blog... me gusta mucho :D.
- [Vim Airline](https://github.com/bling/vim-airline) es de mucha ayuda, brinda información en tiempo real que resulta ser bastante útil, el problema es que torna lento mi Vim, por lo que lo tengo temporalmente desactivado.
- ¿Vundle, Neobundle o Pathogen? Ya escribiré un artículo sobre ello, pero resumo que me quedo con [Vundle](https://github.com/gmarik/vundle) por el momento.
- [Vim Unimpaired](https://github.com/tpope/vim-unimpaired): ¡Amo esta extensión!

Y con respecto al uso de Sublime Text, he de decir que lo abro una o dos veces por semana para usar un par de Snippets de SQL que no he querido migrar a Vim aún, ¿pereza o falta de tiempo? Quizás las dos.

`:bd`
