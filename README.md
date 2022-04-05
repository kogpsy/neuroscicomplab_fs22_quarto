# neuroscicomplab_fs22_quarto

Website and slides for the course "Neurowissenschaft im Computerlab". This repo is based on [neuroscicomplabFS22][1], but instead of using [distill][2] as publishing system, [Quarto][3] is used.

## Development

First of all, make sure to [install Quarto][4]. Since this course has a strong focus on R, R along with all required packages must be installed as well.

If all the dependencies are installed, you have access to those commands while inside the repo:

**`quarto preview`**

This spins up a development server. A browser tab will open which will reload everytime you change the source code.

**`quarto render`**

This will render the whole site and save the result under `docs`.

### File structure

TODO

[1]: https://github.com/kogpsy/neuroscicomplabFS22
[2]: https://pkgs.rstudio.com/distill/
[3]: https://quarto.org/
[4]: https://quarto.org/docs/get-started/
