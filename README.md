<div id="top"></div>


[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/wordcloud.jpg" alt="wordcloud" width="500" height="300">
  </a>
  <h3 align="center">visual representation of words used to highlight popular words and phrases based on frequency and relevance (Persian Version)</h3>
</div>

<br />
<br />

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites & Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">How to Run</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project


<div align="center">
<img src="images/screenshot.png" alt="wordcloud" width="300" height="300">
</div>
  
A word cloud (also known as a tag cloud) is a visual representation of words. Cloud creators are used to highlight popular words and phrases based on frequency and relevance. They provide you with quick and simple visual insights that can lead to more in-depth analyses.

<p align="right">(<a href="#top">back to top</a>)</p>



## Getting Started

this section explain instructions which should be followed to setting up the project. it is easier to run scripts from terminal by passing argument with the help of argparse library and this project also follow this pattern

### Prerequisites & Installation

<ul>
  <li>
    there is a json format file inside <b>src/data</b> named <b>cs_stack</b>. it is initially used as sample data to create wordcloud. it can be replaced by any other json format file extracted from <b>telegram</b>. for doing so:
    <ol type="1">
      <li>enter a chat\channel\group in your telegram. on right corner of page there is menu; open it</li>
      <li>on opened menu, click on export chat history</li>
      <li>on opened menu click on export</li>
      <li>after finishing download, replace it with cs_stack</li>
    </ol>
  </li>
  <li>inside data directory there is file named <b>BHoma.ttf</b> which is used initially as a base font, it can be replaced by any other font file with .ttf format</li>
   <li>install all library specified whithin requirement.txt</li>
</ul>

### How to Run

```sh
git clone https://github.com/semitable/lb-foraging.git
cd lb-foraging
pip install -e .
```

after following <b>Prerequisites</b> section steps and setting up all necessary dependencies follow below steps to run program:

<ul>
  <li><b>clone this repo on your local machine inside that env</b></li>
  <li>
    <p>
      <b>ADD TO PYTHONPATH:</b>
      go to repo directory through terminal and run: <b>export PYTHONPATH=$PWD</b>
    </p>
  </li>
  <li>
    run this: <b>python src/main.py</b>
  </li>
</ul>


<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing


If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

aidin kazempour - [linkdin](https://www.linkedin.com/in/aidin-kazempour-b647811ba/) - aydinkazempour7@gmail.com

Project Link: [https://github.com/ay-ka/WordCloud](https://github.com/ay-ka/WordCloud)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [pytopia - a platform for learning python](https://www.pytopia.ai/)


<p align="right">(<a href="#top">back to top</a>)</p>


[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/aidin-kazempour-b647811ba/
[product-screenshot]: images/screenshot.png
