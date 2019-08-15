# colorcli
Command-line interface (CLI) color themes for tmux, bash and vim by Jonas Jacek

## Colors

<table>
  <tr>
    <th>Xterm Number</th>
    <th>Xterm Name</th>
    <th>HEX</th>
    <th>Usage</th>
  </tr>
  <tr><td>0</td><td>Black <span>(SYSTEM)</span></td><td>#000000</td><td>...</td></tr>
  <tr><td>15</td><td>White <span>(SYSTEM)</span></td><td>#ffffff</td><td>...</td></tr>
  <tr><td>24</td><td>DeepSkyBlue4</td><td>#005f87</td><td>...</td></tr>
  <tr><td>59</td><td>Grey37</td><td>#5f5f5f</td><td>...</td></tr>
  <tr><td>160</td><td>Red3</td><td>#d70000</td><td>bell</td></tr>
  <tr><td>226</td><td>Yellow1</td><td>#ffff00</td><td>highlight</td></tr>
  <tr><td>238</td><td>Grey27</td><td>#444444</td><td>...</td></tr>
  <tr><td>254</td><td>Grey89</td><td>#e4e4e4</td><td>...</td></tr>
  <tr><td>250</td><td>Grey74</td><td>#bcbcbc</td><td>...</td></tr>
</table>

---

## Implementations

* **Bash**  
  Add the snippet in `colorcli.bashrc` to your `.bashrc`, which is one of the configuration file of the [Bash](https://www.gnu.org/software/bash/) shell.
* **tmux**  
  Add the snippet in `colorcli.tmux.conf` to your `.tmux.conf`, which is the configuration file for the [tmux](https://github.com/tmux/tmux/wiki) terminal multiplexer.
* **CMUS**  
  Copy `colorcli.theme` to `/usr/share/cmus/` to use it in the [cmus](https://cmus.github.io/) music player. 
* **Vim**  
  Snippets for the [Vim](https://www.vim.org/) text editor:
  * **Lightline**  
    Add the `colorcli.vim` colorscheme to [Lightline](https://github.com/itchyny/lightline.vim), a statusline/tabline plugin for Vim.
