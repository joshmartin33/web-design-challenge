
<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/joshmartin33/web-design-challenge">
    <img src="assets/images/bootstrap-logo-shadow.png" alt="Logo1" width="110" height="70">
  </a>

<h3 align="center">web-design-challenge</h3>

  <p align="center">
    Latitude
    <br />
    <a href="https://github.com/joshmartin33/web-design-challenge"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://joshmartin33.github.io/web-design-challenge/">View Github pages</a>
    ·
    <a href="https://github.com/joshmartin33/web-design-challenge/issues">Report Bug</a>
  </p>
</div>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#web-requirements">Web Requirements</a></li>
    <li><a href="#considerations">Considerations</a></li>
    <li><a href="#creators">Creators</a></li>
    <li><a href="#citing-and-referencing">Citing and Referencing</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

The Pupose of this project was to design we website based on the analyse on how weather changes as you get closer to the equator. To accomplish this analsis, we pulled data from the OpenWeatherMap API to assemble a dataset on over 500 cities.

After assembling the dataset, we used matplotlib to plot various aspects of the weather vs. latitude. Factors we included: temperature, cloudiness, wind speed and humifity. This site provides the source data and visualisations created as part of the analysis, as well as explanations and descriptions of any trends and correlations witnessed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Web Requirements -->
## Web Requirements

<ul>
    <li>
        <p>My website must consist of seven pages.</p>
    </li>
    <li>
        <p>At the top of every page, my website must have a navigation bar.</p>
    </li>
    <li>
        <p>My website must be deployed to GitHub Pages.</p>
    </li>
</ul>

<br>
<h3><a href="https://github.com/joshmartin33/web-design-challenge">Click here to access the home page</a></h3>
<br>

<p>My website must consist of seven pages as follows:</p>
<ul>
        <li>
            <p>A <a href="https://joshmartin33.github.io/web-design-challenge/index.html">landing page</a> that contains the following elements:</p>
            <ul>
                <li>
                    <p>An explanation of the project.</p>
                </li>
                <li>
                    <p>A link to each visualisation page. For these, a sidebar should contain a preview image of each visualisation. Clicking an image should take the user to that visualisation.</p>
                </li>
            </ul>
        </li>
        <li>
            <p>Four <a href="https://joshmartin33.github.io/web-design-challenge/visualisations/temperature.html">visualisation pages</a>, stored in the <code>visualisations</code> folder, each with the following elements:</p>
            <ul>
                <li>
                    <p>A descriptive title and a heading tag.</p>
                </li>
                <li>
                    <p>The visualisation for the selected comparison (latitude vs. max temperature, latitude vs. humidity, latitude vs. cloudiness, or latitude vs. wind speed). The images that these pages display should be stored in the <code>assets/images</code> folder.</p>
                </li>
                <li>
                    <p>A paragraph describing the visualisation and its significance.</p>
                </li>
            </ul>
        </li>
        <li>
            <p>A <a href="https://joshmartin33.github.io/web-design-challenge/visualisations/comparison.html">comparisons page</a> that does the following:</p>
            <ul>
                <li>
                    <p>Contains all the visualisations on the same page so that people can easily compare them.</p>
                </li>
                <li>
                    <p>Uses a Bootstrap grid for the visualisations. This grid must contain two visualisations across a medium or large screen and one visualisation across an extra-small or small screen.</p>
                </li>
            </ul>
        </li>
        <li>
            <p>A <a href="https://joshmartin33.github.io/web-design-challenge/visualisations/data.html">data page</a> that displays a responsive table containing the data that the visualisations use, as follows:</p>
            <ul>
                <li>
                    <p>The table must be a Bootstrap <code>table</code> component.</p>
                </li>
                <li>
                    <p>The data must come from either exporting or converting the CSV file to HTML. To do so, try using a tool that you already know: Pandas. Pandas has a <code>to_html</code> method that generates an HTML table from a Pandas DataFrame.
                    </p>
                </li>
            </ul>
        </li>
    </ul>



<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- Considerations -->
## Considerations

<ul>
        <li>
            <p>It was a requirement that I must use Bootstrap. This includes using the Bootstrap <code>navbar</code> component for the header on every page, the Bootstrap grid for responsiveness on the comparison page, and the Bootstrap <code>table</code> component for the data page.</p>
        </li>
        <li>
            <p>It was a requirement that I must deploy my website to GitHub Pages, and that as a result, the website must work at a live, publicly accessible URL.</p>
        </li>
        <li>
            <p>I made sure to use a CSS media query that uses Bootstrap and/or <code>@media</code> for the navigation bar.</p>
        </li>
        <li>
            <p>I also made sure that my website works at all window widths.</p>
        </li>
    </ul>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Creators -->
## Creators

Josh Martin - <a href="https://github.com/joshmartin33">GitHub</a>


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Citing and Referencing -->
## Citing and Referencing

* OpenWeatherMap.org. (2022). Сurrent weather and forecast. Retrieved from <a href="https://openweathermap.org/">Link</a>
* getbootstrap.com (2022). Getting started · Bootstrap. Retrieved from <a href="https://getbootstrap.com/">Link</a>


<p align="right">(<a href="#readme-top">back to top</a>)</p>