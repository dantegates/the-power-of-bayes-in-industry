# PyMCon: Afterword

A couple of weeks ago I gave a [talk](https://www.youtube.com/watch?v=7KrspD1TZNU&ab_channel=PyMCDevelopers) for the 2023 [PyMCon Web Series](https://pymcon.com/events/). The aim of the talk was to advocate for the advantages of a _first principles_ approach to modeling which emphasizes the data generating process (DGP). I wanted to conclude the talk with a slide on _tips_ and another with _relevant resources_. However, I felt that 

Although this material didn't make the cut for the talk, I figured it would make a good post, covered in brief.


## Tips

### There's no "right" answer

There's [no book](https://dantegates.github.io/slides/pymcon-2023-webseries.html#/why-industry) that explains the true data generating process in the back (or [is there?](https://www.reddit.com/r/math/comments/8fly2/ever_heard_of_what_erd%C5%91s_called_the_book_here_is/)).

This is worth pointing out because the best of these _first principles_ models seem obvious once you've seen them. The trick is not to be fooled: [_it's approximations all the way down_](https://en.wikipedia.org/wiki/All_models_are_wrong). This part is more of an art than a science, and there are a lot of "degrees of freedom" in how to go about this part.

### Don’t rush to the keyboard

_First principles_ modeling is more about how we frame a problem then the code we write. Take time to sketch, whiteboard or work things out on paper. Then try to code your ideas up once you have a firm understanding of where you want to start.

### Start simple, add assumptions incrementally



### Prior predictive sampling

Do it.

### Think graphically

See [this excellent case study](https://betanalpha.github.io/assets/case_studies/generative_modeling.html).

### Get comfortable with basics of probability

- Know things like [law of total probability](https://en.wikipedia.org/wiki/Law_of_total_probability), rules of [conditional probability](https://en.wikipedia.org/wiki/Conditional_probability) and [joint probability](https://en.wikipedia.org/wiki/Joint_probability_distribution)
- Understand [expectations](https://en.wikipedia.org/wiki/Expected_value). Common gotcha: $\text{E}(f(\theta)) \ne f(\text{E}(\theta))$
- Work out expressions for [conjugate priors](https://en.wikipedia.org/wiki/Conjugate_prior) to build chops

### Challenge yourself to see these problems everywhere

As an example, check out my [quarantine playlist post](https://dantegates.github.io/2020/04/20/my-quarantine-playlist.html).

## Resources

- Putting case study and extensions:
    - [Original](https://mc-stan.org/users/documentation/case-studies/golf.html)
    - [Colab notebook, companion to this talk](https://colab.research.google.com/drive/1luKMwARuZPuu-CVqV_OU5kJTvC5e5Ogs)
    - [PyMC Example Gallery](https://www.pymc.io/projects/examples/en/latest/gallery.html)
- Industry applications that are slightly more generic:
    - [PyMC Labs x Hello Fresh](https://www.pymc-labs.io/blog-posts/reducing-customer-acquisition-costs-how-we-helped-optimizing-hellofreshs-marketing-budget/) Mixed Media Marketing
    - [Pareto/NBD](http://brucehardie.com/notes/009/pareto_nbd_derivations_2005-11-05.pdf)