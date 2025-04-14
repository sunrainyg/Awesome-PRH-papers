# Contributing to Awesome-PRH

## Quick Steps

1. Fork repository
2. Add paper's BibTeX to `citations/paper-name.txt`
3. Add paper entry to README.md in correct section
4. Submit Pull Request

## Example: How to Add a Paper

### Step 1: Add BibTeX Citation

Create a text file in the `citations/` folder:

BibTeX (`citations/prh.txt`):
```bibtex
@InProceedings{huh2024prh,
  title     = {The Platonic Representation Hypothesis},
  author    = {Huh, Minyoung and Cheung, Brian and Wang, Tongzhou and Isola, Phillip},
  booktitle = {Proceedings of the 41st International Conference on Machine Learning},
  year      = {2024}
}
```

### Step 2: Add Paper to README.md

Add your entry to the appropriate section:

README entry:
```html
<tr>
  <td><strong><a href="https://arxiv.org/abs/2405.07987">The Platonic Representation Hypothesis</a></strong><br/>
  <em>Minyoung Huh, Brian Cheung, Tongzhou Wang, Phillip Isola</em><br/>
  <span class="venue-tag icml">ICML 2024</span> <span class="venue-tag oral">Oral</span> | 
  <a href="https://github.com/minyoungg/platonic-rep">github</a> | 
  <a href="citations/prh.txt">bibtex</a></td>
</tr>
```

Need help? [Open an issue](https://github.com/sunrainyg/awesome-PRH/issues/new)
