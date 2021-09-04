<!--
*** This README markdown is built from the following repo
*** https://github.com/othneildrew/Best-README-Template
-->



<!-- PROJECT SHIELDS -->
<!--
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->

  <h3 align="center">Text Classifier</h3>

  <p align="center">
    Classify text into 4 categories (Business, Sci/fi, World, sports)
    <br />
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

The project can be broke down to the following steps:

- import required dependencies
- load and preprocess text data
    - preprocess text using a user-defined function that
    uses `nltk` and `re` to strip text, and remove stopwords, etc.
      
    - split data using split function that uses `sklearn` framework
    - encode data using a user-defined encoder class
    - tokenize the text using a user-defined class
    - one-hot encoding the text user-defined function
    - padding the features using a user-defined function
    - create dataset and dataloader from a user-defined class
    
- build a cnn model based on `torch.nn.Module`
- building a user-defined trainer used for both training and evaluation
- training the model
- evaluating the model
- inference with test sample


### Built With

main frameworks and libraries used in building this project

* [PyTorch](https://pytorch.org)
* [Pandas](https://pandas.pydata.org)
* [sklearn](https://scikit-learn.org/)
* [autopy](https://pypi.org/project/autopy/)
* [nltk](https://www.nltk.org)
* [numpy](https://numpy.org)
* [json](https://www.json.org/json-en.html)

<!-- GETTING STARTED -->
## Getting Started

examine the jupyter notebook and run the cells in the given order to prevent errors

### Prerequisites

make sure you have the following packages installed in your virtual environment.
* pip
  ```sh
  pip install torch
  ```

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Samir Gouda - [https://www.linkedin.com/in/samirgouda](https://www.linkedin.com/in/samirgouda) 

email: [samiir.ahmedd@gmail.com](mailto:samiir.ahmedd@gmail.com)

Project Link: [https://github.com/SamirGouda/text_classifier](https://github.com/SamirGouda/text_classifier)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [Goku Mohandas](https://github.com/GokuMohandas) for his great tutorials





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/samirgouda/
