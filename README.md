# luhmann

Find a productive workflow to use knowledge cards. Repo named after [Niklas Luhmann](https://en.wikipedia.org/wiki/Niklas_Luhmann).

Goal
----

My goal is to manage https://github.com/epogrebnyak/learn better. [learn] is a collection of my markdown notes on programming, data management and teaching of IT, unclassified and not categorised. 

[learn]: https://github.com/epogrebnyak/learn

I would like to:

- [ ] render my notes as a web site on Github pages
- [ ] add Github Actions script to build upon commit
- [ ] present a starting page, index.md or index.html
- [ ] sort or view notes by category, keyword or a tag

I attach less weight to:

- sticking to one specific tool for all my workflow

[Zettelkasten](https://en.wikipedia.org/wiki/Zettelkasten) seems a good 
note-taking philosophy. Coupled with some static generator, hope it can work well. 

### Non-goals and itches

- write a new python package
- better choice of a theme/template for html


What I learned so far
---------------------

- I can use https://github.com/eyeseast/python-frontmatter/ to manage markdown metadata ('front matter')


What I reviewed
---------------

- https://github.com/srid/neuron (very clean, but requires nix for setup, no [drop-in executable] yet)
- https://gitlab.com/sthesing/libzettels (backend lib in Rust, apparently manages index creation)
- https://github.com/crelder/zettelkasten/tree/master/Example_Project/Zettelkastenprogramme (has scripts for specific tasks, but not updated)

[drop-in executable]: https://github.com/srid/neuron/issues/183

