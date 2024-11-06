# History

-

[![Photograph of statues of Newton and Leibniz](./images/newton_leibniz.jpg) <!-- .element: width="1000px" -->](https://commons.wikimedia.org/wiki/File:Statues_of_Isaac_Newton_and_Gottfried_Leibniz.jpg)

Notes:
Two of the finest scientists of the 17th century.
Both claimed to have invented calculus.
Likely that they both did, indepedently.
But neither claim could be proven
because the culture was to be secretive about your work
so you could make money by teaching it to those who wanted to learn.

-

![Photograph of the Royal Society's premises in Crane Court](./images/rs.jpg) <!-- .element: width="700px" -->

Notes:
Around the same time,
the Royal Society gets going.
Motto: "Nullius in Verba" - don't take anyone's word for it.
Starts the first scientific journal,
and promotes the philosophy that for your work to be recognised,
you must publish it,
in such a way that anyone can reproduce and understand it.

-

Process $\rightarrow$ Data $\rightarrow$ Analysis $\rightarrow$ Results

Notes:
The form of a paper was supposed to be this:
you explain what you did,
show what data that gave you,
show what you did to the data,
and then present the results of that process.
Simple,
logical,
and in principle anyone skilled in the art could follow it to reproduce you work.

-

![Photograph of a supercomputer](./images/supercomputer.jpg) <!-- .element: width="1200px" -->

Notes:
This was pretty successful for a few hundred years,
creating science as we know it.
Then in the twentieth century,
we taught sand how to think and gave it anxiety.
Great:
we now have (in principle) fully deterministic machines,
so we can share the exact set of steps,
and they can be reproduced precisely,
without the possibility of human error.

-

![Screen shot of a lot of code in very small font, filling the screen](./images/lots_of_code.png) <!-- .element: width="1800px" -->

Notes:
Unfortunately,
the length of instructions is longer than a typical paper,
even before you include the code of others that you're building on top of.

-

Process $\rightarrow$ ⬛ $\rightarrow$ 🪄 $\rightarrow$ ✨Results✨

Notes:
This,
and some early missteps like
"treating the computer like a piece of lab equipment",
meant that adopting computers actually reduce reproducibility
rather than improved it.

-

_An article about computational science in a scientific publication is **not** the scholarship itself, it is merely **advertising** of the scholarship. The actual scholarship is the complete software development environment and the complete set of instructions which generated the figures._

&mdash;[attributed to Jon Claerbout, around 1995](https://statweb.stanford.edu/~wavelab/Wavelab_850/wavelab.pdf)

Notes:
"Claerbout" rhymes with "share shout".
Returning to where we would like to be:
many people view papers as the ultimate goal.
But if they don't enable reproducibility,
then it is the supporting work
that forms the actual research.

---

# Definitions

-

## Reproducibility

<span class="fragment fade-in" data-fragment-index="1">Same data</span>
<span class="fragment fade-in" data-fragment-index="2">$+$ same analysis</span>
<span class="fragment fade-in" data-fragment-index="3">$\rightarrow$ Same results</span>

<span class="fragment fade-in" data-fragment-index="4">(from [The Turing Way project](https://the-turing-way.netlify.app/reproducible-research/overview/overview-definitions.html))</span>

Notes:
Reproducibility is when you can take the same data,
run the same analysis on it,
and get the same results out at the end.
This sounds trivial&mdash;if
we can't satisfy this requirement,
are we doing science?
All of science is built on the idea
that we can stand on the shoulders of giants;
if those giants change shape depending on who looks at them,
then we are building on quicksand.

-

## Replicability

New data $+$ same analysis $\rightarrow$ Same results

<br>

## Robustness

Same data $+$ new analysis $\rightarrow$ Same results

Notes:
If we don't have reproducibility,
then these are right out.

-

## Open Science

The movement to make all research accessible to all levels of society.

![Papers](images/paper.jpg) <!-- .element width="200px" -->&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![Experimental Samples](images/test_tube.jpg) <!-- .element width="200px" -->](https://www.publicdomainpictures.net/en/view-image.php?image=302908&picture=filling-up-the-test-tube)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Code](images/photo_of_code.jpg) <!-- .element width="200px" --> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![Data](images/photo_of_data.jpg) <!-- .element width="200px" -->

Notes:
In some sense,
this will always be an unachieveable ideal to be strived towards.
The more of society we make our data accessible to,
the more overhead costs pile up.
Try making a petabyte of data downloadable to anyone on the internet
without a business model to pay for the bandwidth and long-term fast storage.

-

## [FAIR](https://www.go-fair.org/fair-principles/)

Data and software should be:

- **F**indable
- **A**ccessible
- **I**nteroperable
- **R**eusable

Notes:
Each of these terms has more detailed definitions;
see the [FAIR Principles](https://www.go-fair.org/fair-principles/).

-

## Persistent identifier

- A long-lasting reference to an object.
- Does not change even if the original moves.
- Ideally, resolves in a web browser.

![DOI](./images/doi.svg) <!-- .element class="fragment" -->

Notes:
You're probably familiar with DOIs as journals give them out for articles
(since journals love to reorganise their websites).

---

# Modest proposals

-

## Croucher’s law

*“I am an idiot and I will make mistakes”*

&mdash;[Mike Croucher](https://mikecroucher.github.io/MLPM_talk/)

Notes:
Human error is inevitable.
We should plan for it,
rather than hope it doesn't affect us.

-

![Comic exhorting us to "automate ALL the things"](./images/automate.png)

(with apologies to [Hyperbole and a Half](https://hyperboleandahalf.blogspot.com))

Notes:
This doesn't bypass human error,
but does make it more detectable and auditable.
We fix an error once,
then it doesn't happen again
(at least for that workflow).
We miss an error,
someone else can spot later exactly where we went wrong.

-

[![Software Carpentry](./images/swc.svg) <!-- .element width="500px" -->](https://software-carpentry.org) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Data Carpentry](./images/dc.svg) <!-- .element width="300px" -->](https://datacarpentry.org)

Notes:
This requires some programming.
Fortunately,
there are organisations that can help with learning to do so.

-

[![Logo of the Data Stewards Network](./images/data-stewards.svg) <!-- .element width="400px" -->](https://datastewards.net/)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Logo of the Society of Research Software Engineering](./images/socrse-knockout.png) <!-- .element width="400px" -->](https://society-rse.org)

Notes:
There is also professionalisation in those who look after data and software,
and train researchers in how to do so.

-

![Papers](./images/paper.jpg) <!-- .element width="100px"  vertical-align="middle" --> ![right arrow](./images/arrow.svg) ![DOI](./images/doi.svg) <!-- .element width="100px"  vertical-align="text-middle" --> 

![Code](./images/photo_of_code.jpg) <!-- .element width="100px"  vertical-align="text-middle" --> <span class="fragment fade-in" data-fragment-index="1"> ![right arrow](./images/arrow.svg) ![DOI](./images/doi.svg) <!-- .element width="100px" vertical-align="text-middle" --></span>

![Data](./images/photo_of_data.jpg) <!-- .element width="100px"  vertical-align="text-middle" --> <span class="fragment fade-in" data-fragment-index="1"> ![right arrow](./images/arrow.svg) ![DOI](./images/doi.svg) <!-- .element width="100px"  vertical-align="text-middle" --></span>

---

# Lattice

-

$$\int \mathcal{D}[\Phi] \mathrm{e}^{-S[\Phi(x, t)]} O[\Phi(x, t)]$$

Notes:
Computational quantum field theorists only want one thing
and it's analytically incalculable.

-

<div style="float: left; width: 60%; height: 100%; vertical-align: middle;">

$$\int \mathcal{D}[\Phi] \mathrm{e}^{-S[\Phi(x, t)]} O[\Phi(x, t)] \\\\
= \lim_{N\rightarrow\infty} \frac{1}{N} \sum_{n=1}^{\infty} O[U]$$

</div>

<div style="float: right; width: 40%; height: 100%; vertical-align: middle;">

![A three-dimensional lattice of points](./images/lattice.svg) <!-- .element style="width: 100%;" -->

</div>

Notes:
So what do?
Computers hate integrals,
so let's discretise everything.
Firstly,
discretise the spacetime to a lattice of points.
Then,
discretise the integral,
so we instead sum over some finite number of samples,
distributed with probability weight $\mathrm{e}^{-S[\Phi]}.
(Note we Wick rotate to Euclidean time so the action can be real.
If $S[\Phi]$ is complex,
e.g. has a chemical potential,
the problem is harder.)
And we can't put Grassman variables into a computer,
so we have to integrte out the fermion fields,
so the state of the system is just the gauge field,
which sits on the links between adjacent sites.

-

- Ensemble: $O(1000)$ configurations
- Typical volume: $96 \times 48^4$
- Space-time dimensions: 4
- $\mathrm{SU}(3)$: $3 \times 3 \times 2$ real numbers
- Double precision: 8 bytes per number

Total: 5.5TiB <!-- .element class="fragment" -->

$O(100\mathrm{k})$ GPUh <!-- .element class="fragment" -->

Notes:
So if the gauge field is the state of our system,
we need to store it so that we can compute observables on it.
Since many observables can be computed on it,
we don't want to throw it away,
but instead share it so that others can make use of it.
But since we typically want more than one point per observable,
we need multiple ensembles.
How do we share tens of terabytes of data?

-

![ILDG logo](./images/ildg.svg) <!-- .element height="100px" -->

![Map of the world showing ILDG regional grids](./images/ildg-map.svg) <!-- .element height="500px" -->

Notes:
The International Lattice Data Grid defines
specifications on how to exchange gauge configurations.
They also provide an identity management service,
and reference implementations for a standards-compatible
metadata catalogue and file catalogue.
The task of deploying these,
and providing storage elements to actually host the binary configurations,
is delegated to Regional Grids.
Currently,
communities are gradually trying to restart their Regional Grids,
after a period of unfunded inactivity.

-

<div style="float: left; width: 40%; height: 100%; vertical-align: middle;">

![Three-dimensional operator with a line connecting sites in the shape of a "+" outlined](./images/lattice_operator.svg)

</div>

<div style="float: left; width: 60%; height: 100%; vertical-align: middle;">

![Zenodo logo](./images/zenodo.svg) <!-- .element height="100px" class="fragment" -->

![Illustration of a piece of text showing citations to software as described in the notes](./images/name-software-with-modifications-editable.svg) <!-- .element height="300px" class="fragment" -->

</div>

Notes:
Once we have generated our ensemble of field configurations,
we then need to actually compute observables on them,
so we can perform the ensemble average that will approximate the integral.
The output of this will typically be much smaller than the configuration,
and the process will require access to the configurations and to HPC resources,
so we will want to share the output of this
so that others can reproduce our subsequent analysis.
Where can we do this?
[click]
Zenodo is one possible location:
it is hosted by CERN,
so is going to be around for a while,
and provides DOIs for records.
Its capacity is limited,
so we can't store configurations there,
but for up to 50GiB per paper it's a good choice.
What about if we want others to be able to reproduce these computations?
[click]
It's not sufficient to describe the algorithm used,
as implementations vary.
We must specify the name of the software used,
so that others may find it.
Even if that software isn't released publicly
(which it should be),
having a name lets readers know if different work used the same software
Specifying a version number lets others know what later changes
you won't have had incorporated when you ran the code.
And providing any changes you made to the software is crucial.

-

![Image showing a diagram of a 3D lattice of points with an arrow pointing to the ILDG logo](./images/lattices-to-ildg.svg) <!-- .element width="400px" -->

![Diagram showing icon representing large blocks of data with an arrow pointing to the HDF5 logo](./images/hdf5-for-more.svg) <!-- .element width="600px" -->

![Diagram showing icons illustrating columned data and plots on the left, with arrows pointing to a CSV file icon on the right](./images/csv-for-columns.svg) <!-- .element width="300px" -->

Notes:
Your data release wants to have raw data,
final data,
metadata and analysis parameters,
and potentially also input files for the HPC computations that led to the raw data.
In terms of data formats,
we already discussed that for configurations we use the ILDG standard formats.
In terms of what we include in our data release,
large data should ideally be packed into a standardised binary format like HDF5.
If your HPC code doesn't produce data such a format,
you can package it,
but it's good to also include the original raw data
in case anything was lost or corrupted in the translation.
Smaller data,
in particular those that non-computational specialists may want access to,
should be a plaintext tabular format like CSV,
that is widely supported by spreadsheet software
in addition to more programmatic data analysis tools.

-

Data $\rightarrow$ ⬛🪄 $\rightarrow$ ✨Results✨

Notes:
Now we have our data in order,
we need to open the black box and look at the analysis more closely.

-

![Plot with default matplotlib style](./images/matplotlib-plot-default.svg) <!-- .element height="300px" -->

![Plot styled to look like in a paper](./images/matplotlib-plot-paper.svg) <!-- .element height="300px" class="fragment" -->
![Plot styled to have a dark background](./images/matplotlib-plot-dark.svg) <!-- .element height="300px" class="fragment" -->

Notes:
Here's a plot in the default Matplotlib plot style.
What if we want it to be more consistent with our paper
[click]
or look good on a presentation with a dark background?
[click]

-

<div style="float: left; width: 700px">

```python
$ head plot_script.py
import matplotlib.pyplot as plt

plt.rcParams["figure.figsize"] = (7, 4)
plt.rcParams["font.size"] = 16
plt.rcParams["axes.labelsize"] = 16
plt.rcParams["legend.fontsize"] = 16
plt.rcParams["lines.markersize"] = 2.0
plt.rcParams["lines.linewidth"] = 0.8
plt.rcParams["lines.markeredgewidth"] = 0.8
plt.rcParams["font.family"] = "lmodern"
plt.rcParams["text.usetex"] = True
plt.rcParams["errorbar.capsize"] = 2
```

</div>

<div style="float: right; width: 500px;" class="fragment">

```python
$ head paper.mplstyle
figure.figsize: 7, 4
font.size: 16
axes.labelsize: 16
legend.fontsize: 16
lines.markersize: 2.0
lines.linewidth: 0.8
lines.markeredgewidth: 0.8
font.family: lmodern
text.usetex: True
errorbar.capsize: 2

$ head plot_script.py
import matplotlib.pyplot as plt
plt.style.use("./paper.mplstyle")
```

</div>

Notes:
One way to achieve this would be 
to manually specify the sequence of formatting options
in each Python script,
or write a helper function to do this.
[click]
But a function to do this is already built into Matplotlib:
you can define a style file containing all your preferences,
and load it in one line each time you plot.
You don't have to use Matplotlib of course;
similar functionality is built into most plotting tools.
The important thing is that you are not manually massaging data.

-

<pre>
Ensemble M1:
mass: 3.1415 ± 0.0926
decay constant: 5.35897 ± 0.00932
Ensemble M2:
mass: 3.84626 ± 0.04338
decay constant: 3.27950 ± 0.00288
Ensemble M3:
mass: 4.1971 ± 0.6939
decay constant: 9.3751 ± 0.0582
Ensemble M4:
mass: 0.97494 ± 0.04592
decay constant: 3.078 ± 0.164
</pre>

</div>

$\downarrow$

<div>

<table>
<tr><th>Ensemble</th><th>$m$</th><th>$f$</th></tr>
<tr><td>M1</td><td><span class="fragment">0.3142(93)</span></td><td><span class="fragment">5.3590(93)</span></td></tr>
<tr><td>M2</td><td><span class="fragment">3.846(43)</span></td><td><span class="fragment">3.2795(29)</span></td></tr>
<tr><td>M3</td><td><span class="fragment">4.20(69)</span></td><td><span class="fragment">9.375(58)</span></td></tr>
<tr><td>M4</td><td><span class="fragment">0.975(46)</span></td><td><span class="fragment">3.08(16)</span></td></tr>
</table>

</div>

Notes:
What about tables?
In a manual workflow,
you might consider transcribing number by hand into your LaTeX documents
from a log file like the one at the top,
or you might drag a CSV file into a table generator,
and copy and paste the result into your paper.
But there's a more automated, reproducible way to do this too.

-

```python
df.to_latex("assets/tables/table1.tex")
```

$\downarrow$

```tex
\begin{table}
    \caption{A spectrum.}
    \input{assets/tables/table1.tex}
\end{table}
```

Notes:
Your code can output a LaTeX file directly,
and the resulting file can be read in from your paper.

-

<div class="r-stack" style="float: left;">

![A paper extract with the text "We find that $g_\mu = 0.0314(15)."](./images/implausible-result.svg) <!-- .element class="fragment fade-out" data-fragment-index="3" width="450px" -->

![A paper extract with the text "We find that $g_\mu = 0.0271(82)."](./images/different-implausible-result.svg) <!-- .element class="fragment current-visible" data-fragment-index="3" width="450px" -->

</div>

<div style="float: right;">

<div class="r-stack" style="width: 600px;">

```tex
\newcommand \gmuResultFinal 0.0314(15)
```
<!-- .element class="fragment current-visible" data-fragment-index="2" -->

```tex
\newcommand \gmuResultFinal 0.0271(82)
```
<!-- .element class="fragment current-visible" data-fragment-index="3" -->

</div>

$\downarrow$ <!-- .element class="fragment" data-fragment-index="2" -->

```tex
\input{definitions.tex}

\begin{document}
We find that $g_\mu = \gmuResultFinal$.
```
<!-- .element class="fragment" data-fragment-index="2" -->


Notes:
We can take this a step further.
Frequently we want to quote numbers in the text of our documents.
Since these numbers will usually be the result of our analysis workflow,
we'd prefer if they could be generated automatically.
In particular,
if you quote many numbers in the text,
or quote one number in many places,
it can be challenging to keep them all consistent by hand
as the analysis is updated.
Similarly to tables,
we output a `.tex` file,
[click]
but in this case we use `\newcommand` to define a macro
that we can use wherever we want to quote a particular number.
When the workflow is re-run,
[click]
updating the `.tex` file will update the numbers everywhere they are used.

-

![Flowchart of the steps in a typical lattice computation](./images/workflow-diagram.svg)

Notes:
Here's a representative, relatively simple lattice analysis workflow.
Each input file might be used to compute multiple observables,
but all classes of file might not be present for all ensembles.
Each output plot may depend on a different subset of ensembles,
or a different set of intermediary parameters.
How might we approach analysing this?

-

![Hands at a keyboard](./images/finger-pressing-computer-keyboard.jpg) <!-- .element height="600px" -->

Notes:
The most naive approach would be to manually invoke each computation by hand.
This would be quite laborious,
and as we discussed earlier,
is prone to errors.
If the data or one of our tools changed,
we'd need to work out what to re-run,
and make sure all the old data were purged.

-

~~~ bash
#!/bin/bash

for ensemble in $(cat ensembles)
do
    for channel in $(cat channels)
        do
        python -m analysis.compute_mass ${ensemble} ${channel} \
            > results/${ensemble}/${channel}.dat
        # ...
    done
    # ...
done

# ...
~~~

Notes:
A shell script is a step up from doing everything by hand,
and is much more auditable later.
Equally,
we could write a Python program that imports our various tools as libraries,
and encode the entire analysis as a Python program that way.
This does however mean that if even if most of our data and code haven't changed,
we still need to re-run everything.
And even if we have steps that don't depend on each other,
we can't easily utilise parallelism and run them at the same time.
We could try and implement such functionality,
checking modification dates,
caching last run times,
and spinning out parallel processes at various points,
but that's a lot of functionality that isn't our specialism&mdash;surely
someone else has encountered this problem before?

-

![Snakemake](./images/snakemake.svg) <!-- .element height="300px" -->

Notes:
Indeed they have;
the problem is "workflow management",
and there is entire zoology of "workflow managers"
that solve some or all of the issues described,
as well as a host of other difficulties.
One popular example,
and one that maps reasonably well to lattice problems,
is Snakemake.

-

~~~ snakemake
plot_styles = "styles/paper.mplstyle"

rule mpcac:
    input:
        data="raw_data/correlators.h5",
        script="src/fit_mpcac.py",
    output:
        data="intermediary_data/{ensemble}/mpcac.json",
        eff_mass_plot="intermediary_data/{ensemble}/mpcac_effmass.pdf",
    conda:
        "envs/fitting.yml"
    shell:
        (
            "python {input.script} {input.data} --output_data {output.data} "
            "--plot_file {output.eff_mass_plot} --plot_styles {plot_styles}"
        )
~~~
<!-- .element style="height: 420px;" -->

~~~ shellsession
snakemake --cores 1 --use-conda intermediary_data/Nf2DB4M2/mpcac.json
~~~

Notes:
In Snakemake,
for each piece of functionality in your workflow,
like "fit a correlator"
or "plot a graph",
you define a rule explaining what inputs it takes,
what outputs it gives back,
and how to run it.
When you ask for a file,
Snakemake works out what rule to run, and runs it.

-

~~~ snakemake
rule all:
    input:
        "assets/plots/mpcac_scan.pdf",


rule mpcac_scan_plot:
    input:
        data=expand("intermediary_data/{ensemble}/mpcac.json", ensemble=ensembles),
        script="src/plot_mpcac.py",
    output:
        plot="assets/plots/mpcac_scan.pdf",
    conda:
        "envs/plotting.yml"
    shell:
        (
            "python {input.script} {input.data} "
            "--plot_file {output.plot} --plot_styles {plot_styles}"
        )
~~~
<!-- .element style="height: 480px;" -->

~~~ shellsession
snakemake --cores 6 --use-conda
~~~

Notes:
If you don't specify a file to build,
Snakemake looks at the first rule in the file
(similarly to `make`),
which is conventionally called `all`.
When you ask for a file that depends on many other files,
Snakemake builds a directed acyclic graph
(DAG)
of the steps needed to achieve it,
and then runs all of the needed steps.
It can use multiple CPU cores to achieve this;
it can also farm work out to clusters.

-

```shellsession
$ cp ensemble1/effective_mass_g5.pdf ../paper/effective_mass_g5_ensemble1.pdf
$ cp ensemble2/effective_mass_gk.pdf ../paper/effective_mass_gk_ensemble2.pdf
$ cp code/analysis/spectrum_summary.pdf ../paper/
$ cp code/analysis/spectrum_summary.tex ../paper/
$ cp code/analysis/metafit.pdf ../paper/
$ cp code/analysis/spectrum_definitions.tex ../paper/
...
```

Notes:
Now,
we've taken steps to generate all of our results automatically,
but there are still some things we're having to do manually&mdash;namely,
keeping all of the TeX and image files we're generating in sync.
If each file is manually copied in when it is changed,
then it is all too easy for some to be forgotten,
meaning that our paper is in an inconsistent state,
where different figures reflect different underlying data.

-

```
$ tree assets
assets
├── definitions
│   └── spectrum.tex
├── plots
│   ├── effective_mass_g5_ensemble1.pdf
│   ├── effective_mass_gk_ensemble2.pdf
│   └── spectrum_summary.pdf
└── tables
    └── spectrum_summary_table.tex

4 directories, 5 files
```

```tex
\includegraphics{assets/plots/spectrum_summary.pdf}
```

Notes:
To avoid this,
it can be a good idea to generate all outputs to be included in a publication
in a single `assets` directory.
This can then be deleted from your LaTeX project and replaced afresh
each time you run your workflow.
When you're ready to publish,
you can also delete the `assets` directory generated by the workflow
and regenerate it completely from scratch,
to make sure that no leftover files from previous runs are present.
There are a couple of things to be careful of:
firstly,
make sure your filenames are all different,
even if they are in different directories.
Otherwise the arXiv will refuse to render your file.
Secondly,
if you publish in Physical Review,
the upload tool completely ignores directory structure,
so the preview PDF will fail to generate.
This doesn't matter&mdash;you can proceed without this,
as the editorial office will do the compilation,
but it's annoying and I've complained at APS repeatedly about this.

---

# Example

-

## [arXiv:2410.19484](https://arxiv.org/abs/2410.19484)

![Screenshot of the cover of the above linked paper](./images/2410.19484.png) <!-- .element width="500" -->

![Screenshot of a section of the above linked paper reading "Research Data Access Statement The data generated for this manuscript can be downloaded from Ref. [14], and the workflow used to analyse it from Ref. [15]. The analysis workflow used to analyse the open data at Ref. [12] is available from Ref. [16]."](./images/2410.19484_data.png) <!-- .element width="1000" -->

Data: [doi:10.5281/zenodo.13128505](https://doi.org/10.5281/zenodo.13128505)

Workflow: [doi:10.5281/zenodo.13128384](https://doi.org/10.5281/zenodo.13128384)

---

# Summary

-

## Data

- Sharing data is good
  - Put a data release on Zenodo
  - Include your raw, unmodified data
  - Include final results, anything that's plotted or tabulated
  - Include metadata and other inputs to your analysis workflow
  - Cite the DOI in your paper

-

## Workflows

- Automate your workflows
  - Use plot styles
  - Output tables and definitions to `.tex`
  - Keep outputs in a single directory, linked into your LaTeX project
  - Snakemake is your friend
  - Use small components
  - Translate manual steps to data
- Share them once they're done
  - Use Zenodo
  - Cite the DOI in your paper
- Working reproducibly takes work but this pays off

-

## Further reading

- Lattice Virtual Academy lecture slides
  on Reproducibility and Open Science:
  https://edbennett.github.io/lava-ros-lectures/
- The TELOS Collaboration Approach
  to Reproducibility and Open Science
  [in preparation]

Notes:
I've only scratched the surface,
there's a lot more discussed in the notes above,
and likely plenty more things that aren't even on my radar.
