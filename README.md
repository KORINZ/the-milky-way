<a name="readme-top"></a>

[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT TITLE -->
<br />
<div align="center">

<h1 align="center">Modeling the Milky Way</h1>

  <p align="center">
    Investigating the absence of alien civilizations in the Milky Way with Python 3.
    <br />
  </p>
</div>

<!-- TABLE OF CONTENTS -->



<!-- ABOUT THE PROJECT -->
## About the Project*

*This project is extracted from the book "Impractical Python Projects" (2019) by Lee Vaughan. Some modifications and additions are made into the original project.

The *Drake equation* is a probability theory used to estimate the number of extraterrestrial civilizations that produce electromagnetic emissions in the Milky Way Galaxy. In this project, the absence of alien radio transmissions will be investigated. The probability of one civilization detecting another will be calculated based on the Drake equation. Finally, a graphical model of the Milky Way will be built.

You can learn more about the Milky Way on its Wikipedia page: https://en.wikipedia.org/wiki/Milky_Way, and the Drake equation: https://en.wikipedia.org/wiki/Drake_equation.

### Prerequisites

Python 3.5 or above is required. In addition, **numpy**, **scipy**, **matplotlib**, **ipython**, **jupyter**, **pandas**, **sympy**, and **nose** modules are also required. You can install them by running the command in your terminal (if you are using pip as your package manager):

```sh
   pip3 install numpy scipy matplotlib ipython jupyter pandas sympy nose
```

### Objective

"For a given number of advanced galactic civilizations and an average radio bubble size, estimate the probability of *any* civilization detecting the radio transmissions of *any* other civilization. For perspective, post the size of the Earth's current radio bubble on a 2D graphical representation of the Milky Way."

-- <cite>"Impractical Python Projects" (p. 189)</cite>

### Strategy

The project is broken down into 4 steps.

1. Estimate the number of transmitting civilizations, $N$, in the Drake equation. The values of parameters are derived from the Wikipedia page of the Drake equation.
2. Choose a size of radio bubble size for these civilizations.
3. Construct a formula for estimating the probability of one civilization detecting another one.
4. Build a graphical model of the Milky Way and post radio emissions bubble from the Earth.

The Drake equation is defined as

$$N = R^*\cdot f_p \cdot n_e \cdot f_l \cdot f_i \cdot f_c \cdot L$$

where  $N$ is the number of civilizations in the Milky Way galaxy with which communication might be possible.
You can check the Wikipedia page of the Drake equation above to see the definitions of other parameters.


## Results

(under construction)

## Additional Future Works

- Modeling IC 1101, one of the largest galaxy in the known universe (under construction)
- Building a galactic empire (under construction)
- Adding habitable zones to the model (under construction)





<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/colin-z/
