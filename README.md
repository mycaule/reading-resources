# Favorite reading resources

Some pointers to read about Software engineering. 

Collected over 10 years in the software industry.

### Videos and Blog posts collection

#### 2020

##### December

- [Google Analytics academy](https://analytics.google.com/analytics/academy/) online course to keep on track with Google Analytics
- [PlantUML](https://plantuml.com) uses good old UML, I use it at my company [for documentation](https://github.com/mycaule/shape-up-plant-uml/), it also provides a nice [plugin for VSCode](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml)

##### November

- [Open Fisca](https://openfisca.org/fr), [Etalab repository](https://github.com/etalab) and [Github for governments](https://government.github.com/community/) has plenty of resources for checking open source governmental algorithms

##### October

- [BigQuery book](https://www.goodreads.com/book/show/50204627-google-bigquery)
- [dbt](https://www.getdbt.com) is a cool modern tool to manage datawarehouse pipelines saving nights of headaches
- a16z [emerging architecture](https://a16z.com/2020/10/15/the-emerging-architectures-for-modern-data-infrastructure/)

##### July

- [`GoogleCloudPlatform/mlops-on-gcp/`](https://github.com/GoogleCloudPlatform/mlops-on-gcp/tree/master/workshops/) has sample bootstrap project of using Kubeflow Pipelines and Argo Workflow. See also [YouTube cast](https://www.youtube.com/watch?v=qx7MLcbCo5g) and the [Pipelines SDK](https://www.kubeflow.org/docs/pipelines/sdk/sdk-overview/)

##### June

- [Srini Devadas and Erik Demaine @ MIT 2011 - Introduction to algorithms](https://www.youtube.com/playlist?list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb) focuses in general ideas rather than in details. One can refer to [Thomas Cormen et al. book](https://www.goodreads.com/book/show/108986.Introduction_to_Algorithms) for a comprehensive list of modern algorithms.
- [Github actions documentation](https://help.github.com/en/actions): is now very mature can help automate some of the things I collected on GitHub and replace old CI systems. Especially it can be used for [ML operations](https://github.blog/2020-06-17-using-github-actions-for-mlops-data-science/) see [YouTube cast](https://www.youtube.com/watch?v=Ll50l3fsoYs) and [`actions-ml-cicd`](https://github.com/machine-learning-apps/actions-ml-cicd)

##### May

- [Architecting with Google Kubernetes Engine Specialization](https://www.coursera.org/specializations/architecting-google-kubernetes-engine) covers all the aspects of using Kubernetes in a professional way, has plenty of hands-on labs and code samples to practice.

##### April

- Corey Schafer video tutorials on Python subjects [Pandas](https://www.youtube.com/playlist?list=PL-osiE80TeTsWmV9i9c58mdDCSskIFdDS), [Matplotlib](https://www.youtube.com/playlist?list=PL-osiE80TeTvipOqomVEeZ1HRrcEvtZB_)
- [James Powell talks at PyData](https://www.youtube.com/watch?v=cKPlPJyQrt4&list=PLJsotIV0ZEQDpIIKhT-33qU1WEefRRrBL) highlights some of the powerful specifics of Python 3, decorators, context manager etc.
- French research labs INRIA also have interesting courses on techniques they use in biostatistics [Recherche reproductible](https://www.fun-mooc.fr/courses/course-v1:inria+41016+self-paced/info), [Python 3](https://www.fun-mooc.fr/courses/course-v1:UCA+107001+session02/info) emphases research versus software engineering

##### March

- [Stéphane Mallat @ Collège de France - Modèles multi-échelles et réseaux de neurones convolutifs](https://www.college-de-france.fr/site/stephane-mallat/course-2019-2020.htm): third consecutive year of expert class to be held weekly about Deep Learning
- [Deep Learning courses @ MIT 2020](https://deeplearning.mit.edu/), the introduction course State of the Art is the most interesting one every year

##### February

- [`photoprism/photoprism`](https://github.com/photoprism/photoprism): Photo Management app powered by Go and TensorFlow. 
Long-term goal to become an open platform for machine learning research based on real-world photo collections.

##### January

- [Laurence Moroney @ Google - Serverless Machine Learning with Tensorflow (course 4 of Data Engineering specialization)](https://www.coursera.org/learn/serverless-machine-learning-gcp?specialization=gcp-data-machine-learning). [Course 3 about Dataflow](https://www.coursera.org/learn/serverless-data-analysis-bigquery-cloud-dataflow-gcp?specialization=gcp-data-machine-learning) is also interesting, _ie._ from _Apache Spark_ to _Apache Beam_ like [Spotify did](https://github.com/spotify/scio).
- [Jeff Dean @ Spark Submit - Large Scale Deep Learning with TensorFlow](https://www.youtube.com/watch?v=XYwIDn00PAo) about convincing the Spark community to use Tensorflow
- [Laurence Moroney @ Google - Recommendation Systems with TensorFlow on GCP (course 5 of Tensorflow specialization)](https://www.coursera.org/learn/recommendation-models-gcp)
- [naphta / tesseract.js](https://github.com/naptha/tesseract.js)
- [ActiveState/gococo](https://github.com/ActiveState/gococo) contains interesting instructions to load a SavedModel directly from a Go application
- [hwalsuklee/awesome-deep-text-detection-recognition](https://github.com/hwalsuklee/awesome-deep-text-detection-recognition): latest advances in text detection and recognition with open source implementations
- Using a similar Tensorflow approach at Airbnb : [1](https://medium.com/airbnb-engineering/categorizing-listing-photos-at-airbnb-f9483f3ab7e3), [2](https://medium.com/airbnb-engineering/amenity-detection-and-beyond-new-frontiers-of-computer-vision-at-airbnb-144a4441b72e)
- [TensorFlow: Data and Deployment DeepLearning.AI specialization](https://www.deeplearning.ai/tensorflow-data-and-deployment/): course #1 on training and running Tensorflow.js is usable for a rearchitecture, course #2, week2 on running TFLite from Kotlin in the JVM is a way to reuse SavedModels without Tensorflow Serving
- [Lex Friedman @ MIT - Deep Learning State of the Art 2020](https://www.youtube.com/watch?v=0VH1Lim8gL8)
- [Zillow - Improving the home selling & buying experience by containerizing ML deployments](https://www.zillow.com/tech/containerizing-ml-deployments/)
- [Data Pipelines with TensorFlow Data Services](https://www.coursera.org/learn/data-pipelines-tensorflow)
- [Rakuten multi-model classifier](http://www.college-de-france.fr/video/stephane-mallat/2020/05-sem-mallat-challenge-rakuten-20200122.mp4)
- [Vox - AI can help find illegal opioid sellers online](https://www.vox.com/recode/2020/1/21/21060680/opioids-artificial-intelligence-illegal-online-pharmacies)

#### 2019

##### December

- [Andrew Ng @ Deeplearning.AI - Structuring Machine Learning Projects](https://www.youtube.com/watch?v=M3qpIzy4MQk&list=PLkDaE6sCZn6E7jZ9sN_xHwSHOdjUxUW_b&index=5) videos 5 to 7 on train/dev/test sets. The [Deep learning specialization](https://www.deeplearning.ai/deep-learning-specialization/) tries to be framework agnostic, but you might be interested to do the online courses from Google about using [Tensorflow in production as well after](https://www.coursera.org/specializations/advanced-machine-learning-tensorflow-gcp).
- [Andrew Ng @ Stanford - Full-Cycle Deep Learning Projects](https://www.youtube.com/watch?v=JUJNGv_sb4Y)
- [Kubeflow on AWS](https://www.kubeflow.org/docs/aws/)

##### November

- [Tencent ML Images / Dictionary and semantic hierarchy](https://github.com/Tencent/tencent-ml-images/blob/master/data/dictionary_and_semantic_hierarchy.txt)
- [Tensorflow / TensorFlow Serving with Docker](https://www.tensorflow.org/tfx/serving/docker) and [AWS Deep Learning AMI / Tensorflow Serving](https://docs.aws.amazon.com/dlami/latest/devguide/tutorial-tfserving.html) to have alternatives ways to run Tensorflow serving locally or on AWS
- [TensorBoard.dev](https://tensorboard.dev/) to share experiments results with stakeholders and project managers.
- [Chrome Extension - URL Rewriter](https://chrome.google.com/webstore/detail/url-rewriter/gpbblpbcnjdnnjdcdclojoonfmpoionh)
- [Jonathan Krause / Stanford - Cars dataset](https://ai.stanford.edu/~jkrause/cars/car_dataset.html)
- Inspiring open source initiatives: [Deezer](https://deezer.io/releasing-spleeter-deezer-r-d-source-separation-engine-2b88985e797e), [Google Jigsaw](https://medium.com/the-false-positive/creating-labeled-datasets-and-exploring-the-role-of-human-raters-56367b6db298)

##### September

- [Pierre Courtiol @ Collège de France - S'attaquer à une compétition de machine learning](https://www.college-de-france.fr/site/stephane-mallat/seminar-2018-02-21-11h15.htm) about tricks to make models perform better and win Kaggle competitions
- [Guillaume Desgens-Pasanau @ CNAM - Protection des données personnelles](https://www.fun-mooc.fr/courses/course-v1:CNAM+01032+session02/about) about applying GDPR laws as engineers.
- [Jeroen Janssens - Data science at the command line](https://www.datascienceatthecommandline.com/).

### Books for Software Engineers

<div align="center">
  <a href="https://www.goodreads.com/book/show/20821304-rethinking-positive-thinking"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1401077636l/20821304.jpg" width=100 alt="Oettingen"/></a>
</div>

<div align="center">
  <a href="https://www.goodreads.com/book/show/1633.Getting_Things_Done"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1312474060l/1633.jpg" width=100 alt="Allen"/></a>
  <a href="https://www.goodreads.com/book/show/22404360-the-pragmatic-programmer"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1431877962l/22404360._SX318_.jpg" width=100 alt="Hunt"/></a>
  <a href="https://www.goodreads.com/book/show/955406.Exceptional_C_"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1348375990l/955406.jpg" width=100 alt="Sutter"/></a>
  <a href="https://www.goodreads.com/book/show/2028395.Applied_Geometry_for_Computer_Graphics_and_CAD"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1348778346l/2028395.jpg" width=100 alt="Marsh"/></a>
  <a href="https://www.goodreads.com/book/show/8910666-eloquent-javascript"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1308260856l/8910666.jpg" width=100 alt="Haverbeke"/></a> 
</div>


<div align="center">
  <a href="https://www.goodreads.com/book/show/8520610-quiet"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1328562861l/8520610.jpg" width=100 alt="Cain"/></a>
  <a href="https://www.goodreads.com/book/show/44936.Refactoring"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1386925632l/44936.jpg" width=100 alt="Fowler"/></a>
  <a href="https://www.goodreads.com/book/show/4845.Code_Complete"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1396837641l/4845.jpg" width=100 alt="McConnell"/></a>
  <a href="https://www.goodreads.com/book/show/840.The_Design_of_Everyday_Things"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1442460745l/840._SY475_.jpg" width=100 alt="Norman"/></a>
  <a href="https://www.goodreads.com/book/show/6593810-learn-you-a-haskell-for-great-good"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1294497489l/6593810.jpg" width=100 alt="Lipovaca"/></a> 
</div>

<div align="center">
  <a href="https://www.goodreads.com/book/show/13541678-functional-programming-in-scala"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1331755294l/13541678.jpg" width=100 alt="Bjarnason"/></a>
  <a href="https://www.goodreads.com/book/show/28129434-les-coulisses-de-la-cr-ation"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1449559205l/28129434._SY475_.jpg" width=100 alt="Villani"/></a>
  <a href="https://www.goodreads.com/book/show/36654771-th-or-me-vivant"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1511553346l/36654771._SX318_.jpg" width=100 alt="Villani"/></a>
  <a href="https://www.goodreads.com/book/show/814670.On_Painting"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1327302825l/814670.jpg" width=100 alt="Alberti"/></a>
  <a href="https://www.goodreads.com/book/show/627206.The_New_Drawing_on_the_Right_Side_of_the_Brain"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1348133732l/627206.jpg" width=100 alt="Edwards"/></a> 
</div>

<div align="center">
  <a href="https://www.goodreads.com/book/show/48021.Innovation_and_Entrepreneurship"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1388250744l/48021.jpg" width=100 alt="Drucker"/></a>
  <a href="https://www.goodreads.com/book/show/1784809.L_il_et_l_Esprit"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1356109828l/1784809.jpg" width=100 alt="Merleau-Ponty"/></a>
  <a href="https://www.goodreads.com/book/show/23463279-designing-data-intensive-applications"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1415816873l/23463279.jpg" width=100 alt="Kleppman"/></a>
  <a href="https://www.goodreads.com/book/show/17623632-functional-javascript"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1369869527l/17623632.jpg" width=100 alt="Fogus"/></a>
  <a href="https://www.goodreads.com/book/show/36264010-l-art"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1505766677l/36264010._SX318_.jpg" width=100 alt="Rodin"/></a> 
</div>

<div align="center">
  <a href="https://www.goodreads.com/book/show/6654728-de-la-division-du-travail-social"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1377449262l/6654728.jpg" width=100 alt="Durkheim"/></a>
  <a href="https://www.goodreads.com/book/show/27968891-site-reliability-engineering"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1459115220l/27968891.jpg" width=100 alt="Beyer"/></a>
  <a href="https://www.goodreads.com/book/show/11095533-lost-in-management"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1330373890l/11095533.jpg" width=100 alt="Dupuy"/></a>
  <a href="https://www.goodreads.com/book/show/8913542-23-things-they-don-t-tell-you-about-capitalism"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1316738602l/8913542.jpg" width=100 alt="Chang"/></a>
  <a href="https://www.goodreads.com/book/show/36502238-le-ons-de-danse-le-ons-de-vie"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1509357303l/36502238._SY475_.jpg" width=100 alt="Byars"/></a> 
</div>

<div align="center">
  <a href="https://www.goodreads.com/book/show/36072.The_7_Habits_of_Highly_Effective_People"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1421842784l/36072.jpg" width=100 alt="Covey"/></a>
  <a href="https://www.goodreads.com/book/show/32296102-advanced-analytics-with-spark"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1489056291l/32296102.jpg" width=100 alt="Ryza"/></a>
  <a href="https://www.goodreads.com/book/show/29094511-amazon-web-services-in-action"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1455470628l/29094511._SX318_.jpg" width=100 alt="Wittig"/></a>
  <a href="https://www.goodreads.com/book/show/17573570-java-se8-for-the-really-impatient"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1387767521l/17573570.jpg" width=100 alt="Horstmann"/></a>
  <a href="https://www.goodreads.com/book/show/36647421-learning-how-to-learn"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1511443712l/36647421._SY475_.jpg" width=100 alt="Oakley"/></a> 
</div>

<div align="center">
  <a href="https://www.goodreads.com/book/show/36453393-functional-programming-simplified"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1508616260l/36453393._SY475_.jpg" width=100 alt="Alexander"/></a>
  <a href="https://www.goodreads.com/book/show/32899495-hands-on-machine-learning-with-scikit-learn-and-tensorflow"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1478536137l/32899495._SX318_.jpg" width=100 alt="Geron"/></a>
  <a href="https://www.goodreads.com/book/show/42832585-graph-algorithms"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1553103782l/42832585.jpg" width=100 alt="Hodler"/></a>
  <a href="https://www.goodreads.com/book/show/108986.Introduction_to_Algorithms"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1387741681l/108986.jpg" width=100 alt="Cormen"/></a>
  <a href="https://www.goodreads.com/book/show/9744812-flourish"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1435373984l/9744812._SX318_.jpg" width=100 alt="Seligman"/></a> 
</div>

### Interesting GitHub repos

<details>
Clean some of the 600+ links already collected
Extract using the GitHub API https://github.com/mycaule?tab=stars
</details>
