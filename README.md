# FractalU: Computational and Behavioral Economics

I'm teaching a class on _computational, behavioral economics_. Details are below; signup link is [here](https://forms.gle/F3YGmLwnjdBgawUx6).

My bio: [Arnav Sood](https://arnavsood.com). I'm a 6th year Econ PhD student at [Carnegie Mellon](https://www.cmu.edu) and a data scientist at [Revelio Labs](https://reveliolabs.com). My thesis is on learning and deception involving "behavioral" (not strictly rational) economic agents.

tl/dr
  - **Time**: Saturdays 2:00-4:00PM. 
  - **Class**: Learn behavioral economics using math and code. Model and code up an economic/social situation you're interested in. 
  - **Duration**: 6 weeks, from 1.16.27 to 2.20.26 
  - **Location**: 223 Sullivan St., NY 10012 (**or Zoom, if you can't make it**)
  - **Cost**: $150 (scholarship), $240 (standard), $300 (supporter). Send me an email at [`arnavs@alumni.cmu.edu`](mailto:arnavs@alumni.cmu.edu) if none of these work.

### Summary 

Over 6 weeks, we're going to use modern machinery (math and code) to explore behavioral economics. By the end, you'll have written a small interactive paper[^1] where you apply these tools to a problem you're interested in. Potential topics include: lying in games, racial discrimination, and partner selection. 

"Economics" means that people are trying to maximize something, subject to some constraint. It may sound rigid (and we'll explore the limits), but this framework is already very permissive. People could be deciding: 
  * Whether or not to accept a job (or spouse), or keep searching. 
  * How much lying they can get away with before reputation effects kick in and punish them. 
  * Whether they're comfortable living in a given neighborhood, or if they should move.

"Behavioral" means that people are not the [precisely rational creatures](https://en.wikipedia.org/wiki/Homo_economicus) required by neoclassical theory. They make mistakes and have limits.

An increasingly large part of modern economics is realizing that these "behavioral frictions" aren't just small annoyances that we can model away. In many cases they lead to startlingly different behavior. 

<!-- They might make mistakes when carrying out their plans. They might process information imperfectly (we'll discuss what that means), or they might face hard limits on the amount of information they can handle.  -->

But we can't see clearly what that behavior is by sticking to the "literary" economics of (say) Keynes. We need to model people mathematically, and then implement our models on a computer.  

### Requirements

You should have **some familiarity** with coding (but you don't need to work as a software engineer or have majored in CS, for example.) Experience with math/stats and git/commandline is a plus, but not a requirement. **No prior economics experience is required**. 

You should be willing to learn and work hard. The course is fast-paced, and you'll get out what you put in. 

### Class Format 

Each class will be 1.5 hours of new material, followed by at least 0.5 hours of coworking and "office hours." (There's no hard stop after 0.5 hours.) We'll usually present the "standard model" of the topic first, and then the version with more realistic/complex behavior. 

Office hours are a good time to get help from me (and other students) on your individual projects. 

There will be homework, but no grades. 

Once everyone is registered, I'll add you all to this repo and make it private. The GitHub will be our main digital space/sandbox. 

After the class is over, anyone who wants to can remove their material or interim products, and I'll make it public again. 

### Syllabus 

Exact topics and order subject to change. **Don't worry if stuff in links seems too advanced**; it's just a reference.

| Class | Topic | Details and References
| -------- | ------- | ------- | ------- | 
| Week 1 (1.16.27) | Setup and Tooling. Intro to JuliaLang. Math Refresher. | [QuantEcon Intro](https://julia.quantecon.org/intro.html)
| Week 2 (1.23.27) | Rationality and Bounded Rationality. | [Simon on Satisficing](https://iiif.library.cmu.edu/file/Simon_box00070_fld05370_bdl0001_doc0001/Simon_box00070_fld05370_bdl0001_doc0001.pdf), [Savage Axioms Revisited](https://www.glennshafer.com/assets/downloads/articles/article25_savage.pdf)
| Week 3 (1.30.27) | Dynamical Systems and Racial Discrimination | [Schelling Segregation Model](https://julia.quantecon.org/multi_agent_models/schelling.html), [Intro to Dynamics](https://julia.quantecon.org/introduction_dynamics/scalar_dynam.html)
| Week 4 (2.6.27)  | Games and Reputation | [Alice in Borderland](https://www.youtube.com/watch?v=i89IO_xVAto), [Rabin on Fairness](https://www.jstor.org/stable/2117561), [Nash on Equilibria](https://www.cs.upc.edu/~ia/nash51.pdf)
| Week 5 (2.13.27) | Persuasion, Communication, and Lying | [Bayesian Persuasion](https://web.stanford.edu/~gentzkow/research/BayesianPersuasion.pdf), [Lying in Games](https://econweb.ucsd.edu/~jsobel/Papers/Lying.pdf)
| Week 6 (2.20.27) | Optimal Stopping and Project Demos! | [Job Search](https://julia.quantecon.org/dynamic_programming/mccall_model.html), [Secretary Problem](https://en.wikipedia.org/wiki/Secretary_problem)


[^1]: A bit on [what this means](https://paulromer.net/jupyter-mathematica-and-the-future-of-the-research-paper/), and an [example](https://github.com/QuantEcon/notebook-gallery/blob/main/ipynb/john_stachurski-coase.ipynb).