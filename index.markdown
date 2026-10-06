---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
last_modified_at: 2023-09-14
---

<style>
.home-awards {
  clear: both;
  display: grid;
  grid-template-columns: minmax(0, 1fr) 400px;
  align-items: center;
  gap: 32px;
  margin: 24px 0 32px;
}

.home-awards-art {
  display: block;
}

.home-awards-art img {
  display: block;
  width: 100%;
  height: auto;
  background: white;
  border-radius: 4px;
}

@media (max-width: 760px) {
  .home-awards {
    grid-template-columns: minmax(0, 1fr);
    gap: 20px;
  }

  .home-awards-art {
    width: 400px;
    max-width: 100%;
    justify-self: center;
  }
}
</style>

I am a mathematician broadly interested in various fields of pure mathematics (algebraic and geometric topology, group theory, dynamics, number theory, and algebraic geometry), mathematics of deep learning, and AI safety and alignment (singular learning theory, training dynamics, and mechanistic interpretability). Starting Fall 2023, I am a Mendelzon-CLTA Assistant Professor in Mathematics at the [Department of Computer and Mathematical Sciences of the University of Toronto Scarborough](https://www.utsc.utoronto.ca/cms/). Previously I was a Postdoctoral Fellow at the University of Toronto, a permanent Research Scientist at the Institute for Information Transmission Problems (Moscow), Assistant Professor at the Moscow Institute of Physics and Technology, and a Postdoctoral Fellow at Skoltech (also Moscow).

In 2019, I got my PhD under the supervision of [Professor **Ernest B. Vinberg**](https://en.wikipedia.org/wiki/Ernest_Vinberg) (see also [here](http://www.ams.org/distribution/mmj/vol8-4-2008/vinberg-birthday.html)). Here you can find my CV, papers, information about my projects and the materials of my teaching courses.

I am one of the organizers of the [Vinberg Distinguished Lecture Series](https://amathr.org/vinberg/). <br><br>

<div class="home-awards">
  <div>
    <p><strong>Awards</strong></p>
    <ul>
      <li>
        2021:
        <a href="https://icm2022.org/blog/the-announcement-of-prize-for-young-russian-mathematicians-winners-among-young-scientists">
          Prize for Young Mathematicians of Russia
        </a>
      </li>
      <li>
        2017, 2018: The Simons Foundation Prize for PhD students.
      </li>
    </ul>
  </div>

  <a class="home-awards-art"
     href="{{ '/assets/gaddg.svg' | relative_url }}">
    <img
      src="{{ '/assets/gaddg.svg' | relative_url }}"
      alt="Geometry, arithmetic and dynamics of discrete groups"
      loading="lazy">
  </a>
</div>

