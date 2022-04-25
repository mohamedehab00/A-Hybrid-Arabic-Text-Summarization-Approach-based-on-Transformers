<div>
  <h2 align="center">A Hybrid Arabic Text Summarization Approach based on Transformers</h2>
</div>

### Abstract :
In this paper, we proposed a sequential hybrid model based on a transformer to summarize Arabic articles. We used two approaches of summarization to make our model. The First is the extractive approach which depends on the most important sentences from the articles to be the summary, so we used Deep Learning techniques specifically transformers such as AraBert to make our summary, The second is abstractive, and this approach is similar to human summarization, which means that it can use some words which have the same meaning but different from the original text. We apply this kind of summary using MT5 Arabic pre-trained transformer model. We sequentially applied these two summarization approaches to building our A3SUT hybrid model. The output of the extractive module is fed into the abstractive module. We enhanced the summary’s quality to be closer to the human summary by applying this approach. 
We add some features to our summary to make it more understandable by applying the metadata generation task "data about data" and classification. By applying metadata generation, we add facilities to our summary, identification, and summary organization.

### IEEE Paper Link : [IEEE Paper]()

### Proposed Approach :

<div align="center">
  <h3>Our Approach Diagram</h3>
  <img src="https://i.ibb.co/x3rvRqR/model.jpg" alt="A3SUT model" width = "900px"/>
</div>

### Data Provided in Data Folder :
<ul>
  <li>EASC ( Extractive Summarization Dataset )</li>
  <li>NADA Corpus ( Text Classification Dataset )</li>
</ul>

### Provided Models :
<ul>
  <li>Classical SVM Model with a Grid Search Optimzation Approach</li>
  <li>Extractive Bert Model : <a href="https://github.com/abdullah-abunada/bert-extractive-summarizer">Model Source</a></li>
  <li>Abstractive mt5 Model : <a href="https://huggingface.co/csebuetnlp/mT5_multilingual_XLSum">Model Source</a></li>
  <li>Meta Data Extraction Model : <a href="https://huggingface.co/marefa-nlp/marefa-ner">Model Source</a></li>
</ul>


### How to run the project :
1. Run the TextClassificationModel.ipynb notebook
> We run this notebook ( only one time ) to train the Text Classification model and convert it to a pickle file to ensure not to train the model each time we use it.
2. Run the MainProject.ipynb notebook
> This notebook is the main notebook which loads all of the models (Text Classification model, Extractive Bert model, Abstractive mt5 model, A3SUT (our hybrid model) and Meta Data Extraction model).
> All outputs are in the Models output section (the last section in MainProject.ipynb).

### Thanks to all project contributors :

<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky"><span style="font-weight:bold;font-style:italic">Contributer Name</span></th>
    <th class="tg-dvpl"><span style="font-weight:bold">LinkedIn</span></th>
    <th class="tg-0lax"><span style="font-weight:bold">GitHub</span></th>
    <th class="tg-0lax"><span style="font-weight:bold">E-mail</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky">Mohamed Ehab</td>
    <td class="tg-dvpl">
      <a href="https://www.linkedin.com/in/mohamedehab00/">
        <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
      </a>
    </td>
    <td class="tg-0lax">
      <a href="https://github.com/mohamedehab00">
        <img src="https://img.shields.io/badge/Github-black?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Badge"/>
      </a>
    </td>
    <td class="tg-0lax">
      <a href = "mailto: mohamed.ehab31450@gmail.com">Send Email</a>
    </td>
  </tr>
  <tr>
    <td class="tg-0pky">Ameen Reda</td>
    <td class="tg-dvpl">
      <a href="https://www.linkedin.com/in/ameen-reda-1b832a184/" target="_blank">
        <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
      </a>
    </td>
    <td class="tg-0lax">
      <a href="https://github.com/AmeenReda1">
        <img src="https://img.shields.io/badge/Github-black?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Badge"/>
      </a>
    </td>
    <td class="tg-0lax">
      <a href = "mailto: ameenreda1@gmail.com">Send Email</a>
    </td>
  </tr>
  <tr>
    <td class="tg-0pky">Ismail Ahmed</td>
    <td class="tg-dvpl">
      <a href="https://www.linkedin.com/in/ismail-ahmed-54a549195/">
        <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
      </a>
    </td>
    <td class="tg-0lax">
      <a href="https://github.com/ismail-1998">
        <img src="https://img.shields.io/badge/Github-black?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Badge"/>
      </a>
    </td>
    <td class="tg-0lax">
      <a href = "mailto: ismail.rammer@gmail.com">Send Email</a>
    </td>
  </tr>
  <tr>
    <td class="tg-0lax">John Adel</td>
    <td class="tg-0lax">
      <a href="https://www.linkedin.com/in/john-adel-18938a1b3/">
        <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
      </a>
    </td>
    <td class="tg-0lax">
      <a href="https://github.com/JohnAdel147">
        <img src="https://img.shields.io/badge/Github-black?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Badge"/>
      </a>
    </td>
    <td class="tg-0lax">
      <a href = "mailto: Mostafa0522magdy@gmail.com">Send Email</a>
    </td>
  </tr>
  <tr>
    <td class="tg-0lax">Mostafa Kafafy</td>
    <td class="tg-0lax">
      <a href="https://www.linkedin.com/in/mostafakafafy0/">
        <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
      </a>
    </td>
    <td class="tg-0lax">
      <a href="https://github.com/kafafy01">
        <img src="https://img.shields.io/badge/Github-black?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Badge"/>
      </a>
    </td>
    <td class="tg-0lax">
      <a href = "mailto: Mostafa0522magdy@gmail.com">Send Email</a>
    </td>
  </tr>
  <tr>
    <td class="tg-0lax">Nada Salah</td>
    <td class="tg-0lax">
      <a href="https://www.linkedin.com/in/nada-salah-2725301a4/">
        <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
      </a>
    </td>
    <td class="tg-0lax">
      <a href="https://github.com/nadasalah99">
        <img src="https://img.shields.io/badge/Github-black?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Badge"/>
      </a> 
    </td>
    <td class="tg-0lax">
      <a href = "mailto: nada191.ns@gmail.com">Send Email</a>
    </td>
  </tr>
 
  <tr>
    <td class="tg-0lax">Assoc. Prof. Ghada Khoriba</td>
    <td class="tg-0lax">
      <a href="https://www.linkedin.com/in/ghada-khoriba-090b72113/">
        <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
      </a>
    </td>
    <td class="tg-0lax">
      <a href="https://github.com/DrGhadaAhmed">
        <img src="https://img.shields.io/badge/Github-black?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Badge"/>
      </a>
    </td>
    <td class="tg-0lax">
      <a href = "mailto: ghada.khoriba@acu.edu.eg">Send Email</a>
    </td>
  </tr>
</tbody>
</table>

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

<div>
  <h2 align="center">Feel Free to Contact us ❤️</h2>
</div>
