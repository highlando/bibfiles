bibfiles
========

repo for my bibfiles

SKM.bib -- contains everything but not in a good shape

diss_bib.bib -- relevant for my phd thesis as in the **ams database format** but persistent and consistent
in the fields 

* notes (-> subtitle. (Translation), Notes) 
* address (city, country/state)
* publisher (full name like Springer-Verlag instead of Springer)
* edition
* volume
* series

For example:

    @BOOK{Zei90a,
     title = {Nonlinear functional analysis and its applications. {II}/{A}},
     publisher = {Springer-Verlag},
     year = {1990},
     author = {Zeidler, Eberhard},
     pages = {xviii+467},
     address = {New York, NY},
     note = {Linear monotone operators, Translated from the German by the author and Leo F. Boron},
     doi = {10.1007/978-1-4612-0985-0},
     isbn = {0-387-96802-4},
     mrclass = {47-02 (35-01 35Dxx 46Nxx 47Bxx 47Hxx)},
     mrnumber = {1033497 (91b:47001)},
     mrreviewer = {Jean Mawhin},
     url = {http://dx.doi.org/10.1007/978-1-4612-0985-0}
    }

or

    @BOOK{GajGZ74,
      title = {Nichtlineare {O}peratorgleichungen und {O}peratordifferentialgleichungen},
      publisher = {Akademie-Verlag},
      year = {1974},
      author = {Gajewski, Herbert and Gr{\"o}ger, Konrad and Zacharias, Klaus},
      volume = {38},
      pages = {ix+281 pp. (loose errata)},
      series = {Mathematische Lehrb{\"u}cher und Monographien},
      address = {Berlin, Germany},
      note = {(Nonlinear Operator Equations and Operator Differential Equations)},
      mrclass = {47HXX (35-02)},
      mrnumber = {0636412 (58 \#30524a)},
      mrreviewer = {H. Triebel}
    }
