## Big reading log

Some useful pointers for Software engineers. Collected over 10 years in the software industry.

### Why?

- To keep track of helpful resources I have referred to during my career
- To help my fellow young colleagues learn quickly

------------------------------

### Table of Contents

- [Posts](#posts-and-webapps) 
  - [2020](#2020) | [2019](#2019) | [2018](#2018) | [2017](#2017) | [2016](#2016)
  - [2015](#2015) | [2014](#2014) | [2013](#2013) | [2012](#2012) | [2011](#2011)
- [Books](#books)
- [Blogs](#blogs-and-podcasts)
  - [Following](#following)
  - [Archives](#archives)
- [Newsletters](#newsletters)
- [Repos](#repos-toolbox-for-work-related-problems)
  - [Node.js](#javascript)
  - [Scala](#scala)
  - [Java](#java)
  - [Python](#python)
  - [Go](#go-and-other-hot-languages)
  - [CLI](#cli)
  - [DevOps](#devops)
  - [Security](#security)

### Talks

- https://gist.github.com/mycaule/636203b3f8f4a9c5eb91f397a63b3e22
- https://gist.github.com/mycaule/39356443c267c0743253282044da16c0
- https://gist.github.com/mycaule/d2f3bc69747aef7f550d2bcc80ec4e63
- https://gist.github.com/mycaule/1776ed63d059eee92d86976e8f399f69

### Posts and Webapps
[back to TOC](#table-of-contents)

#### 2021 Objectives

- Follow Lex Fridman Annual state of the art talk
- Read [Machine Learning Design Patterns](https://www.goodreads.com/book/show/55275019-machine-learning-design-patterns), pass the [GCP certification](https://cloud.google.com/certification/data-engineer)
- Update my blog with interesting contents based on what is here and my gists
- Write a small project in Go language using one of the libraries below
- Write part of a book using https://bookdown.org/yihui/rmarkdown/tufte-handouts.html or https://github.com/scalameta/mdoc

#### 2020
[back to TOC](#table-of-contents)

##### December

- [Google Analytics academy](https://analytics.google.com/analytics/academy/) online course to keep on track with Google Analytics
- [PlantUML](https://plantuml.com) uses good old UML, I use it at my company [for documentation](https://github.com/mycaule/shape-up-plant-uml/), it also provides a nice [plugin for VSCode](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml)
- [Slack Deletron](https://slackdeletron.com)
- [Tips on how to secure](https://github.com/forter/security-101-for-saas-startups/blob/english/security.md) your company quickly
- Great post on how to do [code reviews the right way](https://mtlynch.io/code-review-love/)
- [Financial Times - Visual Vocabulary](https://raw.githubusercontent.com/ft-interactive/chart-doctor/master/visual-vocabulary/poster.png)

##### November

- [Open Fisca](https://openfisca.org/fr), [Etalab repository](https://github.com/etalab) and [Github for governments](https://government.github.com/community/) has plenty of resources for checking open source governmental algorithms
- Deepmind : one documentary on [AlphaGo](https://www.youtube.com/watch?v=WXuK6gekU1Y), Lex Fridman about the advances of [Alphafold2](https://www.youtube.com/watch?v=W7wJDJ56c88)

##### October

- [BigQuery book](https://www.goodreads.com/book/show/50204627-google-bigquery)
- [dbt](https://www.getdbt.com) is a cool modern tool to manage datawarehouse pipelines saving nights of headaches
- a16z [emerging data architectures](https://a16z.com/2020/10/15/the-emerging-architectures-for-modern-data-infrastructure/)

##### July

- [`GoogleCloudPlatform/mlops-on-gcp/`](https://github.com/GoogleCloudPlatform/mlops-on-gcp/tree/master/workshops/) has sample bootstrap project of using Kubeflow Pipelines and Argo Workflow. See also [YouTube cast](https://www.youtube.com/watch?v=qx7MLcbCo5g) and the [Pipelines SDK](https://www.kubeflow.org/docs/pipelines/sdk/sdk-overview/)

##### June

- [Srini Devadas and Erik Demaine @ MIT 2011 - Introduction to algorithms](https://www.youtube.com/playlist?list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb) focuses in general ideas rather than the details. One can refer to [Thomas Cormen et al. book](https://www.goodreads.com/book/show/108986.Introduction_to_Algorithms) for a comprehensive list of modern algorithms.
- [Github actions documentation](https://help.github.com/en/actions): is now very mature can help automate some of the things I collected on GitHub and replace old CI systems. Especially it can be used for [ML operations](https://github.blog/2020-06-17-using-github-actions-for-mlops-data-science/) see [YouTube cast](https://www.youtube.com/watch?v=Ll50l3fsoYs) and [`actions-ml-cicd`](https://github.com/machine-learning-apps/actions-ml-cicd)

##### May

- [Architecting with Google Kubernetes Engine Specialization](https://www.coursera.org/specializations/architecting-google-kubernetes-engine) covers all the aspects of using Kubernetes in a professional context, has plenty of hands-on labs and code samples to practice.

##### April

- Corey Schafer video tutorials on Python subjects [Pandas](https://www.youtube.com/playlist?list=PL-osiE80TeTsWmV9i9c58mdDCSskIFdDS), [Matplotlib](https://www.youtube.com/playlist?list=PL-osiE80TeTvipOqomVEeZ1HRrcEvtZB_)
- [James Powell talks at PyData](https://www.youtube.com/watch?v=cKPlPJyQrt4&list=PLJsotIV0ZEQDpIIKhT-33qU1WEefRRrBL) highlights some of the powerful specifics of Python 3, decorators, context managers etc.
- French research labs INRIA also have interesting courses on techniques they use in biostatistics [Recherche reproductible](https://www.fun-mooc.fr/courses/course-v1:inria+41016+self-paced/info), [Python 3](https://www.fun-mooc.fr/courses/course-v1:UCA+107001+session02/info) emphases research versus software engineering

##### March

- [Stéphane Mallat @ Collège de France - Modèles multi-échelles et réseaux de neurones convolutifs](https://www.college-de-france.fr/site/stephane-mallat/course-2019-2020.htm): third consecutive year of expert class to be held weekly about Deep Learning
- [Deep Learning courses @ MIT 2020](https://deeplearning.mit.edu/), the introduction course State of the Art is the most interesting one every year

##### February

- [`photoprism/photoprism`](https://github.com/photoprism/photoprism): Photo Management app powered by Go and TensorFlow. 
Their long-term goal is to become an open platform for machine learning research based on real-world photo collections.

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
[back to TOC](#table-of-contents)

##### December

- [Andrew Ng @ Deeplearning.AI - Structuring Machine Learning Projects](https://www.youtube.com/watch?v=M3qpIzy4MQk&list=PLkDaE6sCZn6E7jZ9sN_xHwSHOdjUxUW_b&index=5) videos 5 to 7 on train/dev/test sets. The [Deep learning specialization](https://www.deeplearning.ai/deep-learning-specialization/) tries to be framework agnostic, but you might be interested to do the online courses from Google about using [Tensorflow in production as well after](https://www.coursera.org/specializations/advanced-machine-learning-tensorflow-gcp).
- [Andrew Ng @ Stanford - Full-Cycle Deep Learning Projects](https://www.youtube.com/watch?v=JUJNGv_sb4Y)
- [Kubeflow on AWS](https://www.kubeflow.org/docs/aws/)
- [Daily Calm calendar](https://blog.calm.com/blog/2020-daily-calm-calendar), if you haven't tried meditation I suggest you doing the Daily Calm challenge on their smartphone app or directly on [their Youtube channel](https://www.youtube.com/playlist?list=PLgdxvG3Ulbifdn2AAEAKohcNV0w_uIStj).

##### November

- [Tencent ML Images / Dictionary and semantic hierarchy](https://github.com/Tencent/tencent-ml-images/blob/master/data/dictionary_and_semantic_hierarchy.txt)
- [Tensorflow / TensorFlow Serving with Docker](https://www.tensorflow.org/tfx/serving/docker) and [AWS Deep Learning AMI / Tensorflow Serving](https://docs.aws.amazon.com/dlami/latest/devguide/tutorial-tfserving.html) to have alternatives ways to run Tensorflow serving locally or on AWS
- [TensorBoard.dev](https://tensorboard.dev/) to share experiments results with stakeholders and project managers.
- [Chrome Extension - URL Rewriter](https://chrome.google.com/webstore/detail/url-rewriter/gpbblpbcnjdnnjdcdclojoonfmpoionh)
- Inspiring open source initiatives: [Deezer](https://deezer.io/releasing-spleeter-deezer-r-d-source-separation-engine-2b88985e797e), [Google Jigsaw](https://medium.com/the-false-positive/creating-labeled-datasets-and-exploring-the-role-of-human-raters-56367b6db298)

##### September
- [Pierre Courtiol @ Collège de France - S'attaquer à une compétition de machine learning](https://www.college-de-france.fr/site/stephane-mallat/seminar-2018-02-21-11h15.htm) about tricks to make models perform better and win Kaggle competitions

##### March

- [Guillaume Desgens-Pasanau @ CNAM - Protection des données personnelles](https://www.fun-mooc.fr/courses/course-v1:CNAM+01032+session02/about) about applying GDPR laws as engineers.
- [Jeroen Janssens - Data science at the command line](https://www.datascienceatthecommandline.com/)
- [Nick Strayer - Using Awk and R to parse 25TB](https://livefreeordichotomize.com/2019/06/04/using_awk_and_r_to_parse_25tb/)

##### January
- Spring Boot resources from Brian Clozel: [From Zero to Hero with Spring Boot](https://www.youtube.com/watch?v%3DaA4tfBGY6jY), [Under the covers of Spring Boot](https://www.youtube.com/watch?v%3DjDchAEHIht0)
- [Carlos Montecinos Geisse - Python Cheatsheet](https://github.com/wilfredinni/python-cheatsheet)
- Helpful GDPR links: [RGPD (27 avril 2016)](https://eur-lex.europa.eu/legal-content/FR/TXT/HTML/), [loi sur la protection des données personnelles (20 juin 2018)](https://www.legifrance.gouv.fr/affichTexte.do?cidTexte%3DJORFTEXT000037085952%26categorieLien%3Did), [décret d'application (1er août 2018)](https://www.legifrance.gouv.fr/affichTexte.do?cidTexte%3DJORFTEXT000037277401%26categorieLien%3Did), [ordonnance (12 décembre 2018)](https://www.legifrance.gouv.fr/affichTexte.do?cidTexte%3DJORFTEXT000037800506%26categorieLien%3Did), [loi informatique et libertés (6 janvier 1978)](https://www.legifrance.gouv.fr/affichTexte.do;jsessionid%3DE01043CBD5846E38FA526E580DFA2106.tplgfr41s_3?cidTexte%3DLEGITEXT000006068624%26dateTexte%3D20190601), [proposition de règlement ePrivacy](https://ec.europa.eu/digital-single-market/en/proposal-eprivacy-regulation)
- CNIL / GDPR: [Les labels CNIL](https://www.cnil.fr/fr/les-labels-cnil), [Logiciel PIA pour les analyses d'impact](https://www.cnil.fr/fr/outil-pia-telechargez-et-installez-le-logiciel-de-la-cnil)
- Collective actions regarding privacy: [La Quadrature du Net](https://www.laquadrature.net/donnees_perso/), [noyb.eu](https://noyb.eu/), [Videos LQDN](https://video.lqdn.fr/videos/recently-added), [DataGueule](https://www.youtube.com/user/datagueule/videos)
- How to secure your [AWS insfrastructure](https://d1.awsstatic.com/whitepapers/Security/AWS_Security_Best_Practices.pdf)
- Some survival CLI tools for Hadoop on AWS: [awslogs](https://github.com/jorgebastida/awslogs), [hdfs dfs](https://hadoop.apache.org/docs/r2.4.1/hadoop-project-dist/hadoop-common/FileSystemShell.html), [htop](https://github.com/hishamhm/htop)
- Doing data engineering on Microsoft environment: [glances](https://github.com/nicolargo/glances), [mssql-scripter](https://github.com/Microsoft/mssql-scripter), [mssql-tools](https://docs.microsoft.com/en-us/sql/linux/sql-server-linux-setup-tools?view%3Dsql-server-2017), [visidata](https://github.com/saulpw/visidata/), [Azure Data Studio](https://github.com/Microsoft/azuredatastudio), [DBeaver](https://dbeaver.io/)

#### 2018
[back to TOC](#table-of-contents)

##### December
- [AWS Labs - SageMaker examples](https://github.com/awslabs/amazon-sagemaker-examples)
- [Google Dataset Search](https://toolbox.google.com/datasetsearch)
- [Google Research - Seedbank](https://research.google.com/seedbank/)
- Useful notes for Spark: [Tips to Debug Apache Spark](https://databricks.com/blog/2016/10/18/7-tips-to-debug-apache-spark-code-faster-with-databricks.html), [Apache Spark Visualization](https://databricks.com/blog/2015/06/22/understanding-your-spark-application-through-visualization.html), [Submitting User Applications with `spark-submit`](https://aws.amazon.com/fr/blogs/big-data/submitting-user-applications-with-spark-submit/), [Managing memory for Apache Spark](https://aws.amazon.com/fr/blogs/big-data/best-practices-for-successfully-managing-memory-for-apache-spark-applications-on-amazon-emr/), [`ammonite-spark` EMR tutorial](https://gist.github.com/alexarchambault/8e1eec124f00b1c5576a29899ae39569)

##### August
- Spotify Engineering Culture ([part1](https://engineering.atspotify.com/2014/03/27/spotify-engineering-culture-part-1/), [part2](https://engineering.atspotify.com/2014/09/20/spotify-engineering-culture-part-2/))
- [EC2 Instances](https://www.ec2instances.info/)

##### March
- [John Bates, Anthony Joseph - Data Science and Engineering with Spark](https://www.edx.org/xseries/data-science-engineering-apacher-sparktm)
- [Martin Odersky, Heather Miller - Functional programming in Scala Specialization](https://www.coursera.org/specializations/scala)
- [Heather Miller - Distributed Programming](http://dist-prog-book.com/chapter/1/rpc.html)
- Some Scala resources: [Alvin Alexander - Scala cookbook](https://alvinalexander.com/scala), , [47 Degrees - Scala exercises](https://www.scala-exercises.org/), [Homegrown Scala collections](https://www.youtube.com/playlist?list%3DPLJGDHERh23x-4bTASKbtwhhAuP6rYQJqE)
- Playing with Spark EMR and Zeppelin, [Spark SQL Partition discovery](https://spark.apache.org/docs/2.3.1/sql-programming-guide.html%23partition-discovery), [AWS EMR releases](https://docs.aws.amazon.com/en_en/emr/latest/ReleaseGuide/emr-release-5x.html), [gallery of Zeppelin Notebooks](https://github.com/hortonworks-gallery/zeppelin-notebooks)

##### January
- [Kelsey Hightower, Carter Morgan - Scalable microservices](https://eu.udacity.com/course/scalable-microservices-with-kubernetes--ud615)
- Resources for using Nginx: [Diego Plentz - Nginx configuration for improved security and performance](https://gist.github.com/plentz/6737338), [awesome Nginx](https://github.com/agile6v/awesome-nginx)

#### 2017
[back to TOC](#table-of-contents)

##### December
- [Joshua Thijssen - REST Cookbook](http://restcookbook.com/)
- [OWASP Foundation - OWASP Top 10](https://www.owasp.org/images/7/72/OWASP_Top_10-2017_%2528en%2529.pdf.pdf)
- [Andrew Ng - Machine learning](https://www.coursera.org/learn/machine-learning)
- [Jerome Friedman - The Elements of Statistical Learning](https://web.stanford.edu/~hastie/Papers/ESLII.pdf)

##### March
- [AWS Whitepapers](https://aws.amazon.com/fr/whitepapers/)
- [Franz](https://meetfranz.com/)
- [Postman](https://www.getpostman.com/)

#### 2016
[back to TOC](#table-of-contents)

##### December 
- [Kevin van Zonneveld - Bash best practices](https://kvz.io/bash-best-practices.html)

##### June

- [Vincent Driessen - A successful Git branching model](https://nvie.com/posts/a-successful-git-branching-model/)
- [Peter Cottle - Learn git branching](https://learngitbranching.js.org)

##### January

- [Jonathan Boyer - Comprendre Git](https://www.grafikart.fr/formations/git)

#### 2015
[back to TOC](#table-of-contents)

- Node.js resources: [nodejs.org](http://nodejs.org/), [Lodash](http://lodash.com/), [Passport](http://passportjs.org/)
- [Twitter Bootstrap](http://getbootstrap.com/)
- Drawing diagrams with [ASCII Flow](http://asciiflow.com/) and [Web Sequence Diagrams](https://www.websequencediagrams.com/)
- French blog post with all [the passenger information designs](http://sncfunepassionquisepartage.weebly.com/reacuteseau-sncf.html), very cool

#### 2014
[back to TOC](#table-of-contents)

- [Steve Yegge - Good Agile, Bad Agile](http://steve-yegge.blogspot.fr/2006/09/good-agile-bad-agile_27.html) on the trend companies using Agile as a buzzword and not doing it seriously
- [Paul Graham](http://paulgraham.com/ambitious.html) from Y Combinator wrote a list of startup ideas
- [WakeOnLAN](http://lifehacker.com/348197/access-your-computer-anytime-and-save-energy-with-wake+on+lan) is useful for desktop computers you want to use as servers or screenboards only at business hours, you can combine it with `crontab`, check also this [stackoverflow post](https://stackoverflow.com/questions/31588035/bash-one-line-command-to-send-wake-on-lan-magic-packet-without-specific-tool)
- [Benchmarks game](https://benchmarksgame-team.pages.debian.net/benchmarksgame/) compares language and tells who has the fastest implementations of different classical algorithms
- [Solarized theme](http://ethanschoonover.com/solarized) is awesome, at that time screen were more eye aggressive, using this and [f.lux](https://justgetflux.com) helped a lot. [Simple Desktops](http://simpledesktops.com/) had cool distraction-free wallpapers.
- [Explain shell](http://explainshell.com/) provides explanation for Bash one liners
- [SvgCharts4Xsl](http://franklinefrancis.github.com/SvgCharts4Xsl/), one of the first charting library for the web, it doesn't use JavaScript!
- [Generating Word documents](http://sebsauvage.net/wiki/doku.php?id=word_document_generation) from XML was one of my concern, I also had to deal with [RTF files](http://latex2rtf.sourceforge.net/rtfspec_6.html)
- Some civil engineering softwares that were inspirational but that I never really used [Straticad](https://www.terrasol.fr/catalogue/straticad-v2), [Code ASTER](http://www.code-aster.org/V2/spip.php?article180), [GDM](http://gdm.brgm.fr/)
- [French - English](http://www.cyann.net/2010/08/29/traduction-formules-excel-francais-anglais-french-english/) translations for EXCEL formulas, helpful as finding help in English is far more easier, and if your employer locks you with a French operating system
- Some online dictionary for STEM: [Dico BTP](http://www.editions-eyrolles.com/Dico-BTP), [Grand dictionnaire terminologique](http://www.granddictionnaire.com/)
- [Wolfram Alpha](http://www.wolframalpha.com/) was the most impressive website for me as I was from a STEM background and it was one of the first computation intensive cloud experience
- [RATP](http://www.ratp.fr/itineraires/fr/ratp/quartier/plan) had lightweight maps for Paris. Very cool if you didn't want to use Google Maps or Mappy.
- [W3Schools](http://www.w3schools.com/) gave me the basics of modern web layout, I was also interested in colorwheels [1](http://www.sessions.edu/color-calculator), [2](http://www.colorschemer.com/online.html)
- [Secure share](https://securesha.re/) interesting 0-server file-sharing website
- [Learn you a Haskell](http://learnyouahaskell.com/modules), one colleague told me about Haskell, "it is like maths you will like it".

#### 2013
[back to TOC](#table-of-contents)

- Two articles on the difficulty on being a software engineer, at that time I didn't really want to choose a software career path. [Patrick McKenzie - Don't Call Yourself A Programmer](http://www.kalzumeus.com/2011/10/28/dont-call-yourself-a-programmer/), [Jeff Atwood - So You Don't Want to be a Programmer After All](http://www.codinghorror.com/blog/2013/04/so-you-dont-want-to-be-a-programmer-after-all.html).
- Some Delphi links for the museum, [Delphi basics](http://www.delphibasics.co.uk/) was the best online resource to find help for Delphi, [using C++ objects in Delphi](http://rvelthuis.de/articles/articles-cppobjs.html), yes I had to use this dinosaur!
- [Armando Fox, David Patterson - Agile Development Using Ruby on Rails](https://www.edx.org/course/agile-development-using-ruby-on-rails-the-basics) where I learned that software wasn't only about Delphi and C++

#### 2012
[back to TOC](#table-of-contents)

- Martin Fowler - Refactoring
- Andrew Hunt - The Pragmatic Programmer
- Other book recommendations from professionals: [Jeff Atwood](https://blog.codinghorror.com/recommended-reading-for-developers/, [George Stocker](https://stackoverflow.com/questions/388242/the-definitive-c-book-guide-and-list), [Scott Hanselman](https://www.hanselman.com/blog/six-essential-language-agnostic-programming-books)
- [Gérard Degoutte - Aide mémoire de mécanique des sols](http://graduateschool.agroparistech.fr/site.php?id=44&fileid=88)
- Mechanics courses : [Laurent Champaney](https://savoir.ensam.eu/moodle/course/view.php?id=1555), [Ecoles des Mines](http://mms2.ensmp.fr/ressources/ens_polycopies.php)

#### 2011
[back to TOC](#table-of-contents)

- Steve McConnell - Code complete
- Herb Sutter - Exceptional C++
- [Hamish Whittal - Shell scripting](http://www.learnlinux.org.za/courses/build/shell-scripting/shell-scripting.pdf)
- [Eric Pement - Useful one-line scripts for sed](http://sed.sourceforge.net/sed1line.txt)
- Coming from a mechanical engineering background, I also enjoyed _formulaires_-style cheatsheets, [Matthew Miller's for Code Complete](https://www.matthewjmiller.net/files/cc2e_checklists.pdf), [Dave Child on Regular expressions](https://cheatography.com/davechild/cheat-sheets/regular-expressions/), [Design patterns](http://www.webdeveloperjuice.com/demos/cheatsheets/design_pattern_cheatsheet_v1.pdf), [Allen Holub on UML](https://holub.com/uml/). I could also print them in one single piece of paper, which was handy.

#### 2010

- Enjoyed reading Laurent Champaney books on mechanics, [Méthodes d’approximation de Solution pour les problèmes de la physique](https://savoir.ensam.eu/moodle/pluginfile.php/15240/mod_resource/content/1/ApproxSolut-Champaney.pdf) and [Méthodes numériques pour la mécanique](https://savoir.ensam.eu/moodle/pluginfile.php/15241/mod_resource/content/2/MEF_Champaney.pdf), and Olivier Gagliardini's "Cours de béton armé" on [reinforced concrete](http://pp.ige-grenoble.fr/pageperso/gagliaro/enseignement/polyBA_IUP3.pdf). I used these book at my last year internship and my first full-time job

### Books
[back to TOC](#table-of-contents)

<div align="center">
  <a href="https://www.goodreads.com/book/show/50204627-google-bigquery"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1572263929l/50204627._SX318_SY475_.jpg" width=100 alt="Lakshmanan"/></a>
  <a href="https://www.goodreads.com/book/show/20821304-rethinking-positive-thinking"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1401077636l/20821304.jpg" width=100 alt="Oettingen"/></a>
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

### Blogs and Podcasts
[back to TOC](#table-of-contents)

#### Following
[back to TOC](#table-of-contents)

- [Scott Hanselman](https://www.hanselman.com/blog/)
- [AWS Big Data](https://aws.amazon.com/fr/blogs/big-data/)
- [Uber Engineering](https://eng.uber.com/)
- [Duolingo](http://making.duolingo.com/)
- [GitHub Engineering](https://githubengineering.com/)
- [Google Web Team](https://developers.google.com/web/updates/)
- [Datadog](https://www.datadoghq.com/blog/)
- [Andreessen Horowitz](https://a16z.com/)
- [Yann Le Tilly](https://transid.blogspot.com/)
- [Rude Baguette](http://www.rudebaguette.com/)
- [Usine Digitale](https://www.usine-digitale.fr/)

#### Archives
[back to TOC](#table-of-contents)

- http://bimandbeam.typepad.com/bim_beam/
- https://medium.com/@maximebeauchemin
- https://medium.com/javascript-scene
- http://blog.bouygues-construction.com
- http://blogs.solidworks.com/solidworksblog
- http://cpptruths.blogspot.com/
- http://love-python.blogspot.com/
- https://developers.facebook.com/blog/
- https://eng.uber.com
- https://engineeringblog.yelp.com
- https://githubengineering.com
- https://blog.google
- https://www.ibm.com/blogs/research/
- https://www.joelonsoftware.com/
- http://civilfrance.typepad.com/blog/
- http://dwf.blogs.com/beyond_the_paper/
- http://ellipsis-autodesk.typepad.com/blog/
- http://images.math.cnrs.fr/
- http://making.duolingo.com/
- http://martinfowler.com/
- http://perspectives.3ds.com
- http://through-the-interface.typepad.com/through_the_interface/
- http://structurebim.typepad.com/blog/
- http://www.codinghorror.com/blog/
- http://www.industrie.com/it/
- http://www.nouvellefabrique.fr/blog
- http://all-about-airbnb.com/
- http://joegebbia.com/blog
- [Airbnb News](https://blog.atairbnb.com/)
- [Airbnb Engineering](https://medium.com/airbnb-engineering)
- [Meilleurs Agents News](https://www.meilleursagents.com/actualite-immobilier/)
- [Meilleurs Agents Engineering](https://medium.com/meilleursagents-engineering)
- [Zillow Porchlight](https://www.zillow.com/blog/)
- [Zillow Research](https://www.zillow.com/research/)
- [Immobilier Danger](https://www.immobilier-danger.com/)
- [Algolia Engineering](https://blog.algolia.com/)
- [Yelp Engineering](https://engineeringblog.yelp.com/)
- [Joel Spolsky](https://www.joelonsoftware.com/)
- [Atlassian](http://confluence.seloger.com/atlassianblog.wpengine.com/)
- [Li Haoyi](http://www.lihaoyi.com/)
- [IntelliJ Scala Plugin](https://blog.jetbrains.com/scala/)
- [Henri Verdier](http://www.henriverdier.com/)
- [Maxime Beauchemin](https://medium.com/@maximebeauchemin)

##### Newsletters
[back to TOC](#table-of-contents)

- [Database Weekly](https://dbweekly.com/)
- [JavaScript Weekly](https://javascriptweekly.com/)
- [Webops Weekly](https://webopsweekly.com/)

### Repos, toolbox for work-related problems
[back to TOC](#table-of-contents)

#### JavaScript
[back to TOC](#table-of-contents)

- [`aerogear/create-graphql`](https://github.com/aerogear/create-graphql)
- [`agenda/agenda`](https://github.com/agenda/agenda)
- [`alexpate/awesome-design-systems`](https://github.com/alexpate/awesome-design-systems)
- [`algolia/places`](https://github.com/algolia/places)
- [`AmirTugi/tea-school`](https://github.com/AmirTugi/tea-school)
- [`ampproject/amphtml`](https://github.com/ampproject/amphtml)
- [`ant-design/ant-design`](https://github.com/ant-design/ant-design)
- [`apache/incubator-echarts`](https://github.com/apache/incubator-echarts)
- [`appbaseio/reactivesearch`](https://github.com/appbaseio/reactivesearch)
- [`azat-co/http2-express`](https://github.com/azat-co/http2-express)
- [`Baremetrics/calendar`](https://github.com/Baremetrics/calendar)
- [`caiogondim/fast-memoize.js`](https://github.com/caiogondim/fast-memoize.js)
- [`bdickason/node-goodreads`](https://github.com/bdickason/node-goodreads)
- [`bensonruan/Face-Mask`](https://github.com/bensonruan/Face-Mask)
- [`bevacqua/dragula`](https://github.com/bevacqua/dragula)
- [`bigskysoftware/intercooler-js`](https://github.com/bigskysoftware/intercooler-js)
- [`brave/browser-laptop`](https://github.com/brave/browser-laptop)
- [`breejs/bree`](https://github.com/breejs/bree)
- [`chentsulin/awesome-graphql`](https://github.com/chentsulin/awesome-graphql)
- [`choojs/choo`](https://github.com/choojs/choo)
- [`clintonwoo/hackernews-react-graphql`](https://github.com/clintonwoo/hackernews-react-graphql)
- [`cmseaton42/task-easy`](https://github.com/cmseaton42/task-easy)
- [`copy/v86`](https://github.com/copy/v86)
- [`CUTR-at-USF/awesome-transit`](https://github.com/CUTR-at-USF/awesome-transit)
- [`d3/d3-hierarchy`](https://github.com/d3/d3-hierarchy)
- [`date-fns/date-fns`](https://github.com/date-fns/date-fns)
- [`denoland/deno`](https://github.com/denoland/deno)
- [`dinerojs/dinero.js`](https://github.com/dinerojs/dinero.js)
- [`dominictarr/JSONStream`](https://github.com/dominictarr/JSONStream)
- [`dvajs/dva`](https://github.com/dvajs/dva)
- [`e-oj/grabity`](https://github.com/e-oj/grabity)
- [`ebradyjobory/finance.js`](https://github.com/ebradyjobory/finance.js)
- [`ehmicky/cross-platform-node-guide`](https://github.com/ehmicky/cross-platform-node-guide)
- [`eladnava/mailgen`](https://github.com/eladnava/mailgen)
- [`electrode-io/electrode`](https://github.com/electrode-io/electrode)
- [`electron/electron-api-demos`](https://github.com/electron/electron-api-demos)
- [`electron/fiddle`](https://github.com/electron/fiddle)
- [`elsewhencode/project-guidelines`](https://github.com/elsewhencode/project-guidelines)
- [`enquirer/enquirer`](https://github.com/enquirer/enquirer)
- [`ethereum/web3.js`](https://github.com/ethereum/web3.js)
- [`ethereumjs/merkle-patricia-tree`](https://github.com/ethereumjs/merkle-patricia-tree)
- [`expo/expo`](https://github.com/expo/expo)
- [`facebook/create-react-app`](https://github.com/facebook/create-react-app)
- [`firebase/functions-samples`](https://github.com/firebase/functions-samples)
- [`formium/formik`](https://github.com/formium/formik)
- [`gatsbyjs/gatsby`](https://github.com/gatsbyjs/gatsby)
- [`getgauge/taiko`](https://github.com/getgauge/taiko)
- [`github/hotkey`](https://github.com/github/hotkey)
- [`gnab/remark`](https://github.com/gnab/remark)
- [`goldbergyoni/nodebestpractices`](https://github.com/goldbergyoni/nodebestpractices)
- [`googleapis/nodejs-translate`](https://github.com/googleapis/nodejs-translate)
- [`googleapis/nodejs-video-intelligence`](https://github.com/googleapis/nodejs-video-intelligence)
- [`googleapis/nodejs-vision`](https://github.com/googleapis/nodejs-vision)
- [`GoogleCloudPlatform/nodejs-docs-samples`](https://github.com/GoogleCloudPlatform/nodejs-docs-samples)
- [`gothinkster/realworld`](https://github.com/gothinkster/realworld)
- [`guess-js/guess`](https://github.com/guess-js/guess)
- [`googleworkspace/apps-script-samples`](https://github.com/googleworkspace/apps-script-samples)
- [`h2non/videoshow`](https://github.com/h2non/videoshow)
- [`hasura/graphqurl`](https://github.com/hasura/graphqurl)
- [`highcharts/highcharts`](https://github.com/highcharts/highcharts)
- [`hodgef/simple-keyboard`](https://github.com/hodgef/simple-keyboard)
- [`hql287/Manta`](https://github.com/hql287/Manta)
- [`imbrn/v8n`](https://github.com/imbrn/v8n)
- [`indutny/elliptic`](https://github.com/indutny/elliptic)
- [`inorganik/countUp.js`](https://github.com/inorganik/countUp.js)
- [`jakesgordon/javascript-state-machine`](https://github.com/jakesgordon/javascript-state-machine)

###### Tensorflow.js
- [`androidfanatic/tfjs-squats-counter-html`](https://github.com/androidfanatic/tfjs-squats-counter-html)
- [`atanasster/hyperparameters`](https://github.com/atanasster/hyperparameters)
- [`GantMan/nsfw_model`](https://github.com/GantMan/nsfw_model)
- [`huggingface/node-question-answering`](https://github.com/huggingface/node-question-answering)
- [`infinitered/nsfwjs`](https://github.com/infinitered/nsfwjs)

##### File formats
- [`11ways/json-dry`](https://github.com/11ways/json-dry)
- [`adrai/flowchart.js`](https://github.com/adrai/flowchart.js)

##### Medias
- [`0xfe/vexchords`](https://github.com/0xfe/vexchords)
- [`actions-on-google/actions-on-google-nodejs`](https://github.com/actions-on-google/actions-on-google-nodejs)

#### Scala
[back to TOC](#table-of-contents)

- [`47degrees/fetch`](https://github.com/47degrees/fetch)
- [`47degrees/sbt-microsites`](https://github.com/47degrees/sbt-microsites)
- [`ACINQ/eclair`](https://github.com/ACINQ/eclair)
- [`akka/akka-http-quickstart-scala.g8`](https://github.com/akka/akka-http-quickstart-scala.g8)
- [`akka/alpakka`](https://github.com/akka/alpakka)
- [`alexandru/scala-best-practices`](https://github.com/alexandru/scala-best-practices)
- [`alexarchambault/plotly-scala`](https://github.com/alexarchambault/plotly-scala)
- [`alexarchambault/scalacheck-shapeless`](https://github.com/alexarchambault/scalacheck-shapeless)
- [`Algiras/Game-Sandbox`](https://github.com/Algiras/Game-Sandbox)
- [`alvinj/ScalaApacheAccessLogParser`](https://github.com/alvinj/ScalaApacheAccessLogParser)
- [`amplab/succinct`](https://github.com/amplab/succinct)
- [`ashwinbhaskar/functional-way`](https://github.com/ashwinbhaskar/functional-way)
- [`Baeldung/scala-tutorials`](https://github.com/Baeldung/scala-tutorials)
- [`cne1x/sfseize`](https://github.com/cne1x/sfseize)
- [`danburkert/continuum`](https://github.com/danburkert/continuum)
- [`coursier/coursier`](https://github.com/coursier/coursier)
- [`databricks/koalas`](https://github.com/databricks/koalas)
- [`databricks/scala-style-guide`](https://github.com/databricks/scala-style-guide)
- [`DevInsideYou/credit-card-generator-and-validator`](https://github.com/DevInsideYou/credit-card-generator-and-validator)
- [`dghubble/sling`](https://github.com/dghubble/sling)
- [`dgomesbr/ScalaNginxLogParser`](https://github.com/dgomesbr/ScalaNginxLogParser)
- [`fedragon/sbt-todolist`](https://github.com/fedragon/sbt-todolist)
- [`foundweekends/giter8`](https://github.com/foundweekends/giter8)
- [`fpinscala/fpinscala`](https://github.com/fpinscala/fpinscala)
- [`Hydrospheredata/typed-sql`](https://github.com/Hydrospheredata/typed-sql)
- [`iheartradio/ficus`](https://github.com/iheartradio/ficus)
- [`input-output-hk/mantis`](https://github.com/input-output-hk/mantis)

##### Spark and Hadoop
- [`51zero/eel-sdk`](https://github.com/51zero/eel-sdk)
- [`adornes/spark_scala_ml_examples`](https://github.com/adornes/spark_scala_ml_examples)
- [`alexarchambault/ammonite-spark`](https://github.com/alexarchambault/ammonite-spark)
- [`aliyun/aliyun-emapreduce-datasources`](https://github.com/aliyun/aliyun-emapreduce-datasources)
- [`apache/predictionio`](https://github.com/apache/predictionio)
- [`apache/spark`](https://github.com/apache/spark)
- [`awesome-spark/learn-by-examples`](https://github.com/awesome-spark/learn-by-examples)
- [`awesome-spark/spark-gotchas`](https://github.com/awesome-spark/spark-gotchas)
- [`awslabs/deequ`](https://github.com/awslabs/deequ)
- [`Azure/mmlspark`](https://github.com/Azure/mmlspark)
- [`databricks/learning-spark`](https://github.com/databricks/learning-spark)
- [`databricks/tensorframes`](https://github.com/databricks/tensorframes)
- [`delta-io/delta`](https://github.com/delta-io/delta)
- [`GoogleCloudDataproc/initialization-actions`](https://github.com/GoogleCloudDataproc/initialization-actions)
- [`holdenk/spark-testing-base`](https://github.com/holdenk/spark-testing-base)
- [`hortonworks-gallery/zeppelin-notebooks`](https://github.com/hortonworks-gallery/zeppelin-notebooks)

#### Python
[Bbck to TOC](#table-of-contents)

- [`8080labs/pyforest`](https://github.com/8080labs/pyforest)
- [`addok/addok`](https://github.com/addok/addok)
- [`airbnb/knowledge-repo`](https://github.com/airbnb/knowledge-repo)
- [`albumentations-team/albumentations`](https://github.com/albumentations-team/albumentations)
- [`alegrand/SMPE`](https://github.com/alegrand/SMPE)
- [`alexjc/neural-enhance`](https://github.com/alexjc/neural-enhance)
- [`ankush-me/SynthText`](https://github.com/ankush-me/SynthText)
- [`apache/airflow`](https://github.com/apache/airflow)
- [`apache/incubator-mxnet`](https://github.com/apache/incubator-mxnet)
- [`apache/incubator-superset`](https://github.com/apache/incubator-superset)
- [`argman/EAST`](https://github.com/argman/EAST)
- [`astronomer/airflow-guides`](https://github.com/astronomer/airflow-guides)
- [`austin-taylor/code-vault`](https://github.com/austin-taylor/code-vault)
- [`AustinReese/UsedVehicleSearch`](https://github.com/AustinReese/UsedVehicleSearch)
- [`aws/amazon-sagemaker-examples`](https://github.com/aws/amazon-sagemaker-examples)
- [`aws/chalice`](https://github.com/aws/chalice)
- [`CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers`](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers)
- [`BasPH/data-pipelines-with-apache-airflow`](https://github.com/BasPH/data-pipelines-with-apache-airflow)
- [`benoitc/gunicorn`](https://github.com/benoitc/gunicorn)
- [`berdario/pew`](https://github.com/berdario/pew)
- [`biubug6/Face-Detector-1MB-with-landmark`](https://github.com/biubug6/Face-Detector-1MB-with-landmark)
- [`bokeh/bokeh`](https://github.com/bokeh/bokeh)
- [`celery/celery`](https://github.com/celery/celery)
- [`clovaai/CRAFT-pytorch`](https://github.com/clovaai/CRAFT-pytorch)
- [`clovaai/deep-text-recognition-benchmark`](https://github.com/clovaai/deep-text-recognition-benchmark)
- [`codelucas/newspaper`](https://github.com/codelucas/newspaper)
- [`connorferster/handcalcs`](https://github.com/connorferster/handcalcs)
- [`CoreyMSchafer/code_snippets`](https://github.com/CoreyMSchafer/code_snippets)
- [`cquest/dvf_as_api`](https://github.com/cquest/dvf_as_api)
- [`dask/dask-tutorial`](https://github.com/dask/dask-tutorial)
- [`dask/dask`](https://github.com/dask/dask)
- [`DaveParr/snakes_and_lambdas`](https://github.com/DaveParr/snakes_and_lambdas)
- [`davidsandberg/facenet`](https://github.com/davidsandberg/facenet)
- [`dbader/schedule`](https://github.com/dbader/schedule)
- [`deepmind/kinetics-i3d`](https://github.com/deepmind/kinetics-i3d)
- [`deezer/spleeter`](https://github.com/deezer/spleeter)
- [`Delgan/loguru`](https://github.com/Delgan/loguru)
- [`dennybritz/nn-from-scratch`](https://github.com/dennybritz/nn-from-scratch)
- [`devitrylouis/imaging_time_series`](https://github.com/devitrylouis/imaging_time_series)
- [`dmlc/gluon-cv`](https://github.com/dmlc/gluon-cv)
- [`dmlc/treelite`](https://github.com/dmlc/treelite)
- [`dmlc/xgboost`](https://github.com/dmlc/xgboost)
- [`donnemartin/data-science-ipython-notebooks`](https://github.com/donnemartin/data-science-ipython-notebooks)
- [`duolingo/halflife-regression`](https://github.com/duolingo/halflife-regression)
- [`emilwallner/Coloring-greyscale-images`](https://github.com/emilwallner/Coloring-greyscale-images)
- [`explosion/spaCy`](https://github.com/explosion/spaCy)
- [`facebook/prophet`](https://github.com/facebook/prophet)
- [`facebookresearch/hydra`](https://github.com/facebookresearch/hydra)
- [`facebookresearch/semi-supervised-ImageNet1K-models`](https://github.com/facebookresearch/semi-supervised-ImageNet1K-models)
- [`facebookresearch/VideoPose3D`](https://github.com/facebookresearch/VideoPose3D)
- [`fastai/fastai`](https://github.com/fastai/fastai)
- [`fastai/fastpages`](https://github.com/fastai/fastpages)
- [`fivethirtyeight/data`](https://github.com/fivethirtyeight/data)
- [`flairNLP/flair`](https://github.com/flairNLP/flair)
- [`flotpython/course`](https://github.com/flotpython/course)
- [`google/python-fire`](https://github.com/google/python-fire)
- [`GoogleCloudPlatform/ai-platform-samples`](https://github.com/GoogleCloudPlatform/ai-platform-samples)
- [`GoogleCloudPlatform/data-science-on-gcp`](https://github.com/GoogleCloudPlatform/data-science-on-gcp)
- [`GoogleCloudPlatform/getting-started-python`](https://github.com/GoogleCloudPlatform/getting-started-python)
- [`GoogleCloudPlatform/ml-design-patterns`](https://github.com/GoogleCloudPlatform/ml-design-patterns)
- [`GoogleCloudPlatform/python-docs-samples`](https://github.com/GoogleCloudPlatform/python-docs-samples)
- [`GoogleCloudPlatform/realtime-embeddings-matching`](https://github.com/GoogleCloudPlatform/realtime-embeddings-matching)
- [`great-expectations/great_expectations`](https://github.com/great-expectations/great_expectations)
- [`grycap/scar`](https://github.com/grycap/scar)
- [`hill-a/stable-baselines`](https://github.com/hill-a/stable-baselines)
- [`idealo/image-super-resolution`](https://github.com/idealo/image-super-resolution)
- [`idealo/imagededup`](https://github.com/idealo/imagededup)
- [`irmen/Pyrolite`](https://github.com/irmen/Pyrolite)
- [`ismir/mir-datasets`](https://github.com/ismir/mir-datasets)
- [`jakevdp/PythonDataScienceHandbook`](https://github.com/jakevdp/PythonDataScienceHandbook)

##### Tensorflow
- [`ageron/handson-ml`](https://github.com/ageron/handson-ml)
- [`ahkarami/Deep-Learning-in-Production`](https://github.com/ahkarami/Deep-Learning-in-Production)
- [`Amin-Tgz/awesome-tensorflow-2`](https://github.com/Amin-Tgz/awesome-tensorflow-2)
- [`aymericdamien/TensorFlow-Examples`](https://github.com/aymericdamien/TensorFlow-Examples)
- [`google-research/bert`](https://github.com/google-research/bert)
- [`GoogleCloudPlatform/tensorflow-without-a-phd`](https://github.com/GoogleCloudPlatform/tensorflow-without-a-phd)
- [`hainan89/3DHumanPoseEstimation`](https://github.com/hainan89/3DHumanPoseEstimation)
- [`huggingface/awesome-papers`](https://github.com/huggingface/awesome-papers)
- [`huggingface/tflite-android-transformers`](https://github.com/huggingface/tflite-android-transformers)
- [`huggingface/transformers`](https://github.com/huggingface/transformers)
- [`hwalsuklee/awesome-deep-text-detection-recognition`](https://github.com/hwalsuklee/awesome-deep-text-detection-recognition)
- [`horovod/horovod`](https://github.com/horovod/horovod)
- [`ina-foss/inaSpeechSegmenter`](https://github.com/ina-foss/inaSpeechSegmenter)

#### Go and other hot languages
[back to TOC](#table-of-contents)

- [`360EntSecGroup-Skylar/excelize`](https://github.com/360EntSecGroup-Skylar/excelize)
- [`ActiveState/gococo`](https://github.com/ActiveState/gococo)
- [`alda-lang/alda`](https://github.com/alda-lang/alda)
- [`argoproj/argo`](https://github.com/argoproj/argo)
- [`arschles/go-in-5-minutes`](https://github.com/arschles/go-in-5-minutes)
- [`astaxie/beego`](https://github.com/astaxie/beego)
- [`atom-archive/xray`](https://github.com/atom-archive/xray)
- [`avelino/awesome-go`](https://github.com/avelino/awesome-go)
- [`aws/aws-sdk-go`](https://github.com/aws/aws-sdk-go)
- [`bitly/go-simplejson`](https://github.com/bitly/go-simplejson)
- [`bjorng/wings`](https://github.com/bjorng/wings)
- [`chrislusf/gleam`](https://github.com/chrislusf/gleam)
- [`cstate/cstate`](https://github.com/cstate/cstate)
- [`ethereum/go-ethereum`](https://github.com/ethereum/go-ethereum)
- [`go-jira/jira`](https://github.com/go-jira/jira)
- [`go-redis/redis`](https://github.com/go-redis/redis)
- [`gobuffalo/buffalo`](https://github.com/gobuffalo/buffalo)
- [`gobuffalo/pop`](https://github.com/gobuffalo/pop)
- [`gohugoio/hugo`](https://github.com/gohugoio/hugo)
- [`golang/go`](https://github.com/golang/go)
- [`googleforgames/open-match`](https://github.com/googleforgames/open-match)
- [`hybridgroup/gocv`](https://github.com/hybridgroup/gocv)
- [`harlow/kinesis-consumer`](https://github.com/harlow/kinesis-consumer)

#### Java
[back to TOC](#table-of-contents)

- [`addthis/stream-lib`](https://github.com/addthis/stream-lib)
- [`apache/beam`](https://github.com/apache/beam)
- [`apache/calcite`](https://github.com/apache/calcite)
- [`apache/druid`](https://github.com/apache/druid)
- [`apache/incubator-pinot`](https://github.com/apache/incubator-pinot)
- [`apache/tinkerpop`](https://github.com/apache/tinkerpop)
- [`aws/aws-sdk-java`](https://github.com/aws/aws-sdk-java)
- [`aws/aws-sdk-java-v2`](https://github.com/aws/aws-sdk-java-v2)
- [`awslabs/multi-model-server`](https://github.com/awslabs/multi-model-server)
- [`axeleroy/commechezsoi`](https://github.com/axeleroy/commechezsoi)
- [`BafS/Java8-CheatSheet`](https://github.com/BafS/Java8-CheatSheet)
- [`eclipse/deeplearning4j`](https://github.com/eclipse/deeplearning4j)
- [`eugenp/tutorials`](https://github.com/eugenp/tutorials)
- [`facebook/buck`](https://github.com/facebook/buck)
- [`framiere/a-kafka-story`](https://github.com/framiere/a-kafka-story)
- [`google/guava`](https://github.com/google/guava)
- [`graalvm/graalvm-demos`](https://github.com/graalvm/graalvm-demos)
- [`haifengl/smile`](https://github.com/haifengl/smile)

##### Apache Beam
- [`GoogleCloudPlatform/dataflow-contact-center-speech-analysis`](https://github.com/GoogleCloudPlatform/dataflow-contact-center-speech-analysis)
- [`GoogleCloudPlatform/dataflow-opinion-analysis`](https://github.com/GoogleCloudPlatform/dataflow-opinion-analysis)
- [`GoogleCloudPlatform/DataflowTemplates`](https://github.com/GoogleCloudPlatform/DataflowTemplates)
- [`GoogleCloudPlatform/df-ml-anomaly-detection`](https://github.com/GoogleCloudPlatform/df-ml-anomaly-detection)

#### Self-development
[back to TOC](#table-of-contents)

- [`996icu/996.ICU`](https://github.com/996icu/996.ICU)
- [`dreamingechoes/awesome-mental-health`](https://github.com/dreamingechoes/awesome-mental-health)
- [`dylanrees/citizen-science`](https://github.com/dylanrees/citizen-science)
- [`hackerkid/Mind-Expanding-Books`](https://github.com/hackerkid/Mind-Expanding-Books)
- [`iamadamdev/bypass-paywalls-chrome`](https://github.com/iamadamdev/bypass-paywalls-chrome)

#### Museum
[back to TOC](#table-of-contents)

- [`a-nikolaev/curseofwar`](https://github.com/a-nikolaev/curseofwar)
- [`AnthonyCalandra/modern-cpp-features`](https://github.com/AnthonyCalandra/modern-cpp-features)
- [`astralapp/astral`](https://github.com/astralapp/astral)
- [`binhnguyennus/awesome-scalability`](https://github.com/binhnguyennus/awesome-scalability)
- [`chronoxor/FastBinaryEncoding`](https://github.com/chronoxor/FastBinaryEncoding)
- [`cran/ElemStatLearn`](https://github.com/cran/ElemStatLearn)
- [`dotnet/aspnetcore`](https://github.com/dotnet/aspnetcore)
- [`edx/edx-platform`](https://github.com/edx/edx-platform)
- [`etalab/calculette-impots-m-language-parser`](https://github.com/etalab/calculette-impots-m-language-parser)
- [`etalab/covid19-dashboard`](https://github.com/etalab/covid19-dashboard)
- [`etalab/dvf`](https://github.com/etalab/dvf)
- [`ethereum/wiki`](https://github.com/ethereum/wiki)
- [`ethereumbook/ethereumbook`](https://github.com/ethereumbook/ethereumbook)
- [`facebookresearch/faiss`](https://github.com/facebookresearch/faiss)
- [`facebookresearch/fastText`](https://github.com/facebookresearch/fastText)
- [`facebookresearch/wav2letter`](https://github.com/facebookresearch/wav2letter)
- [`fchollet/ARC`](https://github.com/fchollet/ARC)
- [`felixrieseberg/windows95`](https://github.com/felixrieseberg/windows95)
- [`google/filament`](https://github.com/google/filament)
- [`google/or-tools`](https://github.com/google/or-tools)
- [`google/wwwbasic`](https://github.com/google/wwwbasic)
- [`gregoiredavid/france-geojson`](https://github.com/gregoiredavid/france-geojson)
- [`googlecreativelab/quickdraw-dataset`](https://github.com/googlecreativelab/quickdraw-dataset)
- [`h2o/h2o`](https://github.com/h2o/h2o)
- [`igorbarinov/awesome-bitcoin`](https://github.com/igorbarinov/awesome-bitcoin)
- [`imposters-handbook/sample-code`](https://github.com/imposters-handbook/sample-code)
- [`intoli/intoli-article-materials`](https://github.com/intoli/intoli-article-materials)
- [`invideu/invid-verification-plugin`](https://github.com/invideu/invid-verification-plugin)

#### DevOps
[back to TOC](#table-of-contents)

- [`actions/starter-workflows`](https://github.com/actions/starter-workflows)
- [`agarrharr/awesome-static-website-services`](https://github.com/agarrharr/awesome-static-website-services)
- [`allinurl/goaccess`](https://github.com/allinurl/goaccess)
- [`awesome-selfhosted/awesome-selfhosted`](https://github.com/awesome-selfhosted/awesome-selfhosted)
- [`aws-samples/ecs-refarch-cloudformation`](https://github.com/aws-samples/ecs-refarch-cloudformation)
- [`aws-samples/lambda-refarch-image-moderation-chatbot`](https://github.com/aws-samples/lambda-refarch-image-moderation-chatbot)
- [`aws-samples/lambda-refarch-imagerecognition`](https://github.com/aws-samples/lambda-refarch-imagerecognition)
- [`aws/aws-sam-cli`](https://github.com/aws/aws-sam-cli)
- [`awsdocs/aws-cloudformation-user-guide`](https://github.com/awsdocs/aws-cloudformation-user-guide)
- [`awsdocs/aws-doc-sdk-examples`](https://github.com/awsdocs/aws-doc-sdk-examples)
- [`awslabs/aws-cloudformation-templates`](https://github.com/awslabs/aws-cloudformation-templates)
- [`awslabs/ec2-spot-labs`](https://github.com/awslabs/ec2-spot-labs)
- [`axa-group/Parsr`](https://github.com/axa-group/Parsr)
- [`cablespaghetti/kubeadm-aws`](https://github.com/cablespaghetti/kubeadm-aws)
- [`balena-io/etcher`](https://github.com/balena-io/etcher)
- [`brotandgames/ciao`](https://github.com/brotandgames/ciao)
- [`cloudtools/troposphere`](https://github.com/cloudtools/troposphere)
- [`devspace/awesome-github-templates`](https://github.com/devspace/awesome-github-templates)
- [`docker-slim/docker-slim`](https://github.com/docker-slim/docker-slim)
- [`dokku/dokku`](https://github.com/dokku/dokku)
- [`donnemartin/awesome-aws`](https://github.com/donnemartin/awesome-aws)
- [`GoogleCloudPlatform/gcsfuse`](https://github.com/GoogleCloudPlatform/gcsfuse)
- [`GoogleCloudPlatform/mlops-on-gcp`](https://github.com/GoogleCloudPlatform/mlops-on-gcp)
- [`GoogleCloudPlatform/training-data-analyst`](https://github.com/GoogleCloudPlatform/training-data-analyst)
- [`healthchecks/healthchecks`](https://github.com/healthchecks/healthchecks)
- [`imgproxy/imgproxy`](https://github.com/imgproxy/imgproxy)

#### Databases
[back to TOC](#table-of-contents)

- [`citusdata/postgresql-hll`](https://github.com/citusdata/postgresql-hll)
- [`citusdata/postgresql-topn`](https://github.com/citusdata/postgresql-topn)
- [`dgraph-io/dgraph`](https://github.com/dgraph-io/dgraph)
- [`ept/ddia-references`](https://github.com/ept/ddia-references)
- [`fastogt/fastonosql`](https://github.com/fastogt/fastonosql)
- [`fishtown-analytics/dbt`](https://github.com/fishtown-analytics/dbt)
- [`getredash/redash`](https://github.com/getredash/redash)
- [`GoogleCloudPlatform/bigquery-oreilly-book`](https://github.com/GoogleCloudPlatform/bigquery-oreilly-book)
- [`GoogleCloudPlatform/bigquery-utils`](https://github.com/GoogleCloudPlatform/bigquery-utils)
- [`heathermiller/dist-prog-book`](https://github.com/heathermiller/dist-prog-book)
- [`HTTPArchive/bigquery`](https://github.com/HTTPArchive/bigquery)
- [`HTTPArchive/httparchive.org`](https://github.com/HTTPArchive/httparchive.org)
- [`influxdata/influxdb`](https://github.com/influxdata/influxdb)

#### CLI
[back to TOC](#table-of-contents)

- [`agarrharr/awesome-cli-apps`](https://github.com/agarrharr/awesome-cli-apps)
- [`akavel/up`](https://github.com/akavel/up)
- [`AlDanial/cloc`](https://github.com/AlDanial/cloc)
- [`alebcay/awesome-shell`](https://github.com/alebcay/awesome-shell)
- [`alex000kim/nsfw_data_scraper`](https://github.com/alex000kim/nsfw_data_scraper)
- [`alexellis/mine-with-docker`](https://github.com/alexellis/mine-with-docker)
- [`andmarti1424/sc-im`](https://github.com/andmarti1424/sc-im)
- [`aria2/aria2`](https://github.com/aria2/aria2)
- [`awslabs/aws-shell`](https://github.com/awslabs/aws-shell)
- [`awslabs/git-secrets`](https://github.com/awslabs/git-secrets)
- [`benibela/xidel`](https://github.com/benibela/xidel)
- [`BurntSushi/ripgrep`](https://github.com/BurntSushi/ripgrep)
- [`BurntSushi/xsv`](https://github.com/BurntSushi/xsv)
- [`bzg/org-mode`](https://github.com/bzg/org-mode)
- [`clibs/entr`](https://github.com/clibs/entr)
- [`clvv/fasd`](https://github.com/clvv/fasd)
- [`cmatsuoka/figlet`](https://github.com/cmatsuoka/figlet)
- [`coursera-dl/edx-dl`](https://github.com/coursera-dl/edx-dl)
- [`dbcli/mssql-cli`](https://github.com/dbcli/mssql-cli)
- [`dbcli/pgcli`](https://github.com/dbcli/pgcli)
- [`dbohdan/structured-text-tools`](https://github.com/dbohdan/structured-text-tools)
- [`dflemstr/rq`](https://github.com/dflemstr/rq)
- [`ericchiang/pup`](https://github.com/ericchiang/pup)
- [`EverythingMe/ncdu-s3`](https://github.com/EverythingMe/ncdu-s3)
- [`exiftool/exiftool`](https://github.com/exiftool/exiftool)
- [`ggreer/the_silver_searcher`](https://github.com/ggreer/the_silver_searcher)
- [`github/hub`](https://github.com/github/hub)
- [`github/semantic`](https://github.com/github/semantic)
- [`HazyResearch/pdftotree`](https://github.com/HazyResearch/pdftotree)
- [`herrbischoff/awesome-command-line-apps`](https://github.com/herrbischoff/awesome-command-line-apps)
- [`holman/spark`](https://github.com/holman/spark)
- [`idank/explainshell`](https://github.com/idank/explainshell)
- [`iterative/dvc`](https://github.com/iterative/dvc)

#### Security
[back to TOC](#table-of-contents)

- [`hak5/bashbunny-payloads`](https://github.com/hak5/bashbunny-payloads)
- [`brannondorsey/wifi-cracking`](https://github.com/brannondorsey/wifi-cracking)


- [`jamesramsay/hercule`](https://github.com/jamesramsay/hercule)
- [`jared-nelsen/LeetCode-Problems`](https://github.com/jared-nelsen/LeetCode-Problems)
- [`jarun/ddgr`](https://github.com/jarun/ddgr)
- [`jarun/googler`](https://github.com/jarun/googler)
- [`jasperes/bash-yaml`](https://github.com/jasperes/bash-yaml)
- [`jaspervz/todo-http4s-doobie`](https://github.com/jaspervz/todo-http4s-doobie)
- [`jeffbski/wait-on`](https://github.com/jeffbski/wait-on)
- [`jehiah/json2csv`](https://github.com/jehiah/json2csv)
- [`jeroenjanssens/data-science-at-the-command-line`](https://github.com/jeroenjanssens/data-science-at-the-command-line)
- [`jgthms/bulma`](https://github.com/jgthms/bulma)
- [`jhc-systems/sqlest`](https://github.com/jhc-systems/sqlest)
- [`jiahaog/nativefier`](https://github.com/jiahaog/nativefier)
- [`jorgebastida/awslogs`](https://github.com/jorgebastida/awslogs)
- [`jorgebastida/gordon`](https://github.com/jorgebastida/gordon)
- [`josdejong/mathjs`](https://github.com/josdejong/mathjs)
- [`js13kGames/resources`](https://github.com/js13kGames/resources)
- [`jtoy/awesome-tensorflow`](https://github.com/jtoy/awesome-tensorflow)
- [`JuliaLang/julia`](https://github.com/JuliaLang/julia)
- [`julianpeeters/sbt-avrohugger`](https://github.com/julianpeeters/sbt-avrohugger)
- [`juliuste/projections`](https://github.com/juliuste/projections)
- [`juliuste/sncf`](https://github.com/juliuste/sncf)
- [`jupyterlab/jupyterlab`](https://github.com/jupyterlab/jupyterlab)
- [`justadudewhohacks/face-api.js`](https://github.com/justadudewhohacks/face-api.js)
- [`justadudewhohacks/opencv4nodejs`](https://github.com/justadudewhohacks/opencv4nodejs)
- [`jvican/sbt-release-early`](https://github.com/jvican/sbt-release-early)

#### K, L letter
- [`kabbi159/awesome-image-tagging`](https://github.com/kabbi159/awesome-image-tagging)
- [`kailuowang/henkan`](https://github.com/kailuowang/henkan)
- [`kaituoxu/Conv-TasNet`](https://github.com/kaituoxu/Conv-TasNet)
- [`kamranahmedse/git-standup`](https://github.com/kamranahmedse/git-standup)
- [`karpathy/convnetjs`](https://github.com/karpathy/convnetjs)
- [`karpathy/neuraltalk2`](https://github.com/karpathy/neuraltalk2)
- [`kasvith/kache`](https://github.com/kasvith/kache)
- [`KaTeX/KaTeX`](https://github.com/KaTeX/KaTeX)
- [`kelseyhightower/kubernetes-the-hard-way`](https://github.com/kelseyhightower/kubernetes-the-hard-way)
- [`keplergl/kepler.gl`](https://github.com/keplergl/kepler.gl)
- [`keras-team/autokeras`](https://github.com/keras-team/autokeras)
- [`keycloak/keycloak`](https://github.com/keycloak/keycloak)
- [`kfei/slack-cleaner`](https://github.com/kfei/slack-cleaner)
- [`khaosdoctor/gotql`](https://github.com/khaosdoctor/gotql)
- [`KKBOX/spark-deployer`](https://github.com/KKBOX/spark-deployer)
- [`klaussinani/signale`](https://github.com/klaussinani/signale)
- [`klaussinani/taskbook`](https://github.com/klaussinani/taskbook)
- [`koalaman/shellcheck`](https://github.com/koalaman/shellcheck)
- [`krishnaik06/Kaggle-Competitions`](https://github.com/krishnaik06/Kaggle-Competitions)
- [`ks888/LambStatus`](https://github.com/ks888/LambStatus)
- [`ktoso/sbt-jmh`](https://github.com/ktoso/sbt-jmh)
- [`kubeflow/kubeflow`](https://github.com/kubeflow/kubeflow)
- [`Kulbear/deep-learning-coursera`](https://github.com/Kulbear/deep-learning-coursera)
- [`kvfrans/deepcolor`](https://github.com/kvfrans/deepcolor)
- [`kwhitley/treeize`](https://github.com/kwhitley/treeize)
- [`kxbmap/configs`](https://github.com/kxbmap/configs)
- [`kymatio/kymatio`](https://github.com/kymatio/kymatio)
- [`labstack/echo`](https://github.com/labstack/echo)
- [`lagom/lagom`](https://github.com/lagom/lagom)
- [`LappleApple/awesome-leading-and-managing`](https://github.com/LappleApple/awesome-leading-and-managing)
- [`lastpass/lastpass-cli`](https://github.com/lastpass/lastpass-cli)
- [`laurenshareshian/home_price_estimator`](https://github.com/laurenshareshian/home_price_estimator)
- [`LeCoupa/awesome-cheatsheets`](https://github.com/LeCoupa/awesome-cheatsheets)
- [`ledger/ledger`](https://github.com/ledger/ledger)
- [`lerna/lerna`](https://github.com/lerna/lerna)
- [`lesnitsky/git-tutor`](https://github.com/lesnitsky/git-tutor)
- [`lesovsky/pgcenter`](https://github.com/lesovsky/pgcenter)
- [`Lewuathe/COVID19-SIR`](https://github.com/Lewuathe/COVID19-SIR)
- [`lhartikk/naivechain`](https://github.com/lhartikk/naivechain)
- [`libfuse/sshfs`](https://github.com/libfuse/sshfs)
- [`libretro/RetroArch`](https://github.com/libretro/RetroArch)
- [`libvips/libvips`](https://github.com/libvips/libvips)
- [`lightbend/config`](https://github.com/lightbend/config)
- [`lightbend/paradox`](https://github.com/lightbend/paradox)
- [`lihaoyi/Ammonite`](https://github.com/lihaoyi/Ammonite)
- [`lihaoyi/requests-scala`](https://github.com/lihaoyi/requests-scala)
- [`lihaoyi/sourcecode`](https://github.com/lihaoyi/sourcecode)
- [`LINCnil/pia-back`](https://github.com/LINCnil/pia-back)
- [`linkedin/detext`](https://github.com/linkedin/detext)
- [`linkedin/isolation-forest`](https://github.com/linkedin/isolation-forest)
- [`lmonkiewicz/spring-rest-validation`](https://github.com/lmonkiewicz/spring-rest-validation)
- [`lmoroney/dlaicourse`](https://github.com/lmoroney/dlaicourse)
- [`localForage/localForage`](https://github.com/localForage/localForage)
- [`lokesh/color-thief`](https://github.com/lokesh/color-thief)
- [`lovell/sharp`](https://github.com/lovell/sharp)
- [`lucidsoftware/relate`](https://github.com/lucidsoftware/relate)
- [`lukechilds/keyv`](https://github.com/lukechilds/keyv)

#### M letter
- [`m2dsupsdlclass/lectures-labs`](https://github.com/m2dsupsdlclass/lectures-labs)
- [`machine-learning-apps/actions-ml-cicd`](https://github.com/machine-learning-apps/actions-ml-cicd)
- [`machine-learning-projects/machine-learning-recipes`](https://github.com/machine-learning-projects/machine-learning-recipes)
- [`mafintosh/csv-parser`](https://github.com/mafintosh/csv-parser)
- [`magenta/magenta-studio`](https://github.com/magenta/magenta-studio)
- [`mahnazkoupaee/WikiHow-Dataset`](https://github.com/mahnazkoupaee/WikiHow-Dataset)
- [`mapbox/pixelmatch`](https://github.com/mapbox/pixelmatch)
- [`mapbox/polylabel`](https://github.com/mapbox/polylabel)
- [`marcelduran/yslow`](https://github.com/marcelduran/yslow)
- [`MarcSkovMadsen/awesome-streamlit`](https://github.com/MarcSkovMadsen/awesome-streamlit)
- [`marcus-nl/scala-impatient-2nd-ed`](https://github.com/marcus-nl/scala-impatient-2nd-ed)
- [`marcuslonnberg/sbt-docker`](https://github.com/marcuslonnberg/sbt-docker)
- [`MarkCLewis/BigDataAnalyticswithSpark`](https://github.com/MarkCLewis/BigDataAnalyticswithSpark)
- [`martin-gorner/tensorflow-mnist-tutorial`](https://github.com/martin-gorner/tensorflow-mnist-tutorial)
- [`martin-gorner/tensorflow-rnn-shakespeare`](https://github.com/martin-gorner/tensorflow-rnn-shakespeare)
- [`mathjax/MathJax`](https://github.com/mathjax/MathJax)
- [`maticzav/emma-cli`](https://github.com/maticzav/emma-cli)
- [`mattermost/mattermost-server`](https://github.com/mattermost/mattermost-server)
- [`matze/mtheme`](https://github.com/matze/mtheme)
- [`maxchehab/CSS-Keylogging`](https://github.com/maxchehab/CSS-Keylogging)
- [`mbadry1/DeepLearning.ai-Summary`](https://github.com/mbadry1/DeepLearning.ai-Summary)
- [`MBKraus/Predicting_real_estate_prices_using_scikit-learn`](https://github.com/MBKraus/Predicting_real_estate_prices_using_scikit-learn)
- [`mdn/webextensions-examples`](https://github.com/mdn/webextensions-examples)
- [`mdr/ascii-graphs`](https://github.com/mdr/ascii-graphs)
- [`meetfranz/franz`](https://github.com/meetfranz/franz)
- [`mermaid-js/mermaid`](https://github.com/mermaid-js/mermaid)
- [`metabase/metabase`](https://github.com/metabase/metabase)
- [`metakirby5/codi.vim`](https://github.com/metakirby5/codi.vim)
- [`mhinz/vim-galore`](https://github.com/mhinz/vim-galore)
- [`MhLiao/TextBoxes_plusplus`](https://github.com/MhLiao/TextBoxes_plusplus)
- [`mholt/archiver`](https://github.com/mholt/archiver)
- [`mholt/PapaParse`](https://github.com/mholt/PapaParse)
- [`michael-lazar/rtv`](https://github.com/michael-lazar/rtv)
- [`microlinkhq/async-ratelimiter`](https://github.com/microlinkhq/async-ratelimiter)
- [`microlinkhq/metascraper`](https://github.com/microlinkhq/metascraper)
- [`microsoft/CNTK`](https://github.com/microsoft/CNTK)
- [`microsoft/DMTK`](https://github.com/microsoft/DMTK)
- [`microsoft/forecasting`](https://github.com/microsoft/forecasting)
- [`microsoft/just`](https://github.com/microsoft/just)
- [`microsoft/LightGBM`](https://github.com/microsoft/LightGBM)
- [`microsoft/MS-DOS`](https://github.com/microsoft/MS-DOS)
- [`microsoft/mssql-scripter`](https://github.com/microsoft/mssql-scripter)
- [`microsoft/napajs`](https://github.com/microsoft/napajs)
- [`microsoft/QuantumKatas`](https://github.com/microsoft/QuantumKatas)
- [`microsoft/recommenders`](https://github.com/microsoft/recommenders)
- [`mikeal/r2`](https://github.com/mikeal/r2)
- [`mikefarah/yq`](https://github.com/mikefarah/yq)
- [`mindsdb/mindsdb`](https://github.com/mindsdb/mindsdb)
- [`minio/minio`](https://github.com/minio/minio)
- [`mithrandie/csvq`](https://github.com/mithrandie/csvq)
- [`mittagessen/kraken`](https://github.com/mittagessen/kraken)
- [`mixu/markdown-styles`](https://github.com/mixu/markdown-styles)
- [`mkdocs/mkdocs`](https://github.com/mkdocs/mkdocs)
- [`ml5js/ml5-examples`](https://github.com/ml5js/ml5-examples)
- [`ml874/Data-Engineering-on-GCP-Cheatsheet`](https://github.com/ml874/Data-Engineering-on-GCP-Cheatsheet)
- [`mlangc/ml-weather-basel-blog`](https://github.com/mlangc/ml-weather-basel-blog)
- [`mlflow/mlflow`](https://github.com/mlflow/mlflow)
- [`mljs/savitzky-golay`](https://github.com/mljs/savitzky-golay)
- [`mobxjs/mobx`](https://github.com/mobxjs/mobx)
- [`monitoringartist/grafana-aws-cloudwatch-dashboards`](https://github.com/monitoringartist/grafana-aws-cloudwatch-dashboards)
- [`MonsantoCo/cloudformation-template-generator`](https://github.com/MonsantoCo/cloudformation-template-generator)
- [`MontFerret/ferret`](https://github.com/MontFerret/ferret)
- [`mourner/flatbush`](https://github.com/mourner/flatbush)
- [`mozilla/readability`](https://github.com/mozilla/readability)
- [`mptre/yank`](https://github.com/mptre/yank)
- [`mrvautin/expressCart`](https://github.com/mrvautin/expressCart)
- [`mvdan/sh`](https://github.com/mvdan/sh)
- [`mysticatea/npm-run-all`](https://github.com/mysticatea/npm-run-all)

#### N letter

- [`naptha/tesseract.js`](https://github.com/naptha/tesseract.js)
- [`Narthorn/ctf`](https://github.com/Narthorn/ctf)
- [`nathanpeck/awesome-ecs`](https://github.com/nathanpeck/awesome-ecs)
- [`NaturalNode/natural`](https://github.com/NaturalNode/natural)
- [`nchammas/flintrock`](https://github.com/nchammas/flintrock)
- [`neherlab/covid19_scenarios`](https://github.com/neherlab/covid19_scenarios)
- [`nektos/act`](https://github.com/nektos/act)
- [`nemo/scrape`](https://github.com/nemo/scrape)
- [`nemtsov/json-mask`](https://github.com/nemtsov/json-mask)
- [`neo4j-contrib/neo4j-graph-algorithms`](https://github.com/neo4j-contrib/neo4j-graph-algorithms)
- [`neovim/neovim`](https://github.com/neovim/neovim)
- [`Netflix/atlas`](https://github.com/Netflix/atlas)
- [`Netflix/falcor`](https://github.com/Netflix/falcor)
- [`Netflix/metaflow`](https://github.com/Netflix/metaflow)
- [`Netflix/pollyjs`](https://github.com/Netflix/pollyjs)
- [`neutraltone/awesome-stock-resources`](https://github.com/neutraltone/awesome-stock-resources)
- [`nextcloud/nextcloudpi`](https://github.com/nextcloud/nextcloudpi)
- [`nhn/tui.calendar`](https://github.com/nhn/tui.calendar)
- [`nicolargo/glances`](https://github.com/nicolargo/glances)
- [`nicolas-van/sonant-x-live`](https://github.com/nicolas-van/sonant-x-live)
- [`nileshkulkarni/csm`](https://github.com/nileshkulkarni/csm)
- [`nk412/optparse`](https://github.com/nk412/optparse)
- [`node-gh/gh`](https://github.com/node-gh/gh)
- [`node-red/node-red`](https://github.com/node-red/node-red)
- [`nok/sklearn-porter`](https://github.com/nok/sklearn-porter)
- [`nolanlawson/optimize-js`](https://github.com/nolanlawson/optimize-js)
- [`norvig/pytudes`](https://github.com/norvig/pytudes)
- [`novakov-alexey/scala-service.g8`](https://github.com/novakov-alexey/scala-service.g8)
- [`nsqio/nsq`](https://github.com/nsqio/nsq)
- [`nteract/hydrogen`](https://github.com/nteract/hydrogen)
- [`nteract/nteract`](https://github.com/nteract/nteract)
- [`nuxt/nuxt.js`](https://github.com/nuxt/nuxt.js)
- [`NVIDIA/vid2vid`](https://github.com/NVIDIA/vid2vid)

#### O letter

- [`oclif/oclif`](https://github.com/oclif/oclif)
- [`octobox/octobox`](https://github.com/octobox/octobox)
- [`official-stockfish/Stockfish`](https://github.com/official-stockfish/Stockfish)
- [`ohmyzsh/ohmyzsh`](https://github.com/ohmyzsh/ohmyzsh)
- [`oliver-moran/jimp`](https://github.com/oliver-moran/jimp)
- [`omerbsezer/Fast-Pytorch`](https://github.com/omerbsezer/Fast-Pytorch)
- [`oneapi-src/oneDNN`](https://github.com/oneapi-src/oneDNN)
- [`onelang/OneLang`](https://github.com/onelang/OneLang)
- [`opencollab/scilab`](https://github.com/opencollab/scilab)
- [`openexchangerates/accounting.js`](https://github.com/openexchangerates/accounting.js)
- [`openfisca/openfisca-france`](https://github.com/openfisca/openfisca-france)
- [`openfisca/openfisca-paris`](https://github.com/openfisca/openfisca-paris)
- [`OptimalBits/redbird`](https://github.com/OptimalBits/redbird)
- [`optimizely/hyperloglog`](https://github.com/optimizely/hyperloglog)
- [`oracle/graal`](https://github.com/oracle/graal)
- [`oracle/python-cx_Oracle`](https://github.com/oracle/python-cx_Oracle)
- [`osquery/osquery`](https://github.com/osquery/osquery)
- [`ostera/tldr.jsx`](https://github.com/ostera/tldr.jsx)
- [`overleaf/overleaf`](https://github.com/overleaf/overleaf)
- [`ovity/octotree`](https://github.com/ovity/octotree)
- [`PacktPublishing/Scala-for-Machine-Learning-Second-Edition`](https://github.com/PacktPublishing/Scala-for-Machine-Learning-Second-Edition)
- [`PAIR-code/facets`](https://github.com/PAIR-code/facets)
- [`panrafal/depthy`](https://github.com/panrafal/depthy)
- [`panzerdp/voca`](https://github.com/panzerdp/voca)
- [`papers-we-love/papers-we-love`](https://github.com/papers-we-love/papers-we-love)
- [`paperswithcode/sota-extractor`](https://github.com/paperswithcode/sota-extractor)
- [`pathikrit/better-files`](https://github.com/pathikrit/better-files)
- [`paulhoughton/mortgage`](https://github.com/paulhoughton/mortgage)
- [`paulp/sbt-extras`](https://github.com/paulp/sbt-extras)
- [`pcgrenier/nifi-examples`](https://github.com/pcgrenier/nifi-examples)
- [`pcm-dpc/COVID-19`](https://github.com/pcm-dpc/COVID-19)
- [`pcottle/learnGitBranching`](https://github.com/pcottle/learnGitBranching)
- [`pd4d10/octohint`](https://github.com/pd4d10/octohint)
- [`peco/peco`](https://github.com/peco/peco)
- [`peterbraden/node-opencv`](https://github.com/peterbraden/node-opencv)
- [`petervanderdoes/gitflow-avh`](https://github.com/petervanderdoes/gitflow-avh)
- [`philc/vimium`](https://github.com/philc/vimium)
- [`phoboslab/underrun`](https://github.com/phoboslab/underrun)
- [`photoprism/photoprism`](https://github.com/photoprism/photoprism)
- [`picturepan2/responsive-resizer`](https://github.com/picturepan2/responsive-resizer)
- [`picturepan2/spectre`](https://github.com/picturepan2/spectre)
- [`PiercingDan/spark-Jupyter-AWS`](https://github.com/PiercingDan/spark-Jupyter-AWS)
- [`pilwon/node-google-finance`](https://github.com/pilwon/node-google-finance)
- [`pimutils/khal`](https://github.com/pimutils/khal)
- [`Pirionfr/pyLinky`](https://github.com/Pirionfr/pyLinky)
- [`pjreddie/darknet`](https://github.com/pjreddie/darknet)
- [`plamere/OrganizeYourMusic`](https://github.com/plamere/OrganizeYourMusic)
- [`plantuml/plantuml`](https://github.com/plantuml/plantuml)
- [`pnxtech/hydra`](https://github.com/pnxtech/hydra)
- [`polynote/polynote`](https://github.com/polynote/polynote)
- [`pomber/git-history`](https://github.com/pomber/git-history)
- [`PostgREST/postgrest`](https://github.com/PostgREST/postgrest)
- [`postmanlabs/httpbin`](https://github.com/postmanlabs/httpbin)
- [`postmanlabs/postman-code-generators`](https://github.com/postmanlabs/postman-code-generators)
- [`powdahound/ec2instances.info`](https://github.com/powdahound/ec2instances.info)
- [`PrefectHQ/prefect`](https://github.com/PrefectHQ/prefect)
- [`prestodb/presto`](https://github.com/prestodb/presto)
- [`prisma-labs/graphql-prisma-typescript`](https://github.com/prisma-labs/graphql-prisma-typescript)
- [`prisma/graphcool-framework`](https://github.com/prisma/graphcool-framework)
- [`prisma/prisma1`](https://github.com/prisma/prisma1)
- [`probmods/webppl`](https://github.com/probmods/webppl)
- [`probot/probot`](https://github.com/probot/probot)
- [`proj4js/proj4js`](https://github.com/proj4js/proj4js)
- [`projectdiscovery/naabu`](https://github.com/projectdiscovery/naabu)
- [`propelml/propel`](https://github.com/propelml/propel)
- [`ProseMirror/prosemirror`](https://github.com/ProseMirror/prosemirror)
- [`przemyslawpluta/node-youtube-dl`](https://github.com/przemyslawpluta/node-youtube-dl)
- [`pstadler/ticker.sh`](https://github.com/pstadler/ticker.sh)
- [`puppeteer/puppeteer`](https://github.com/puppeteer/puppeteer)
- [`pureconfig/pureconfig`](https://github.com/pureconfig/pureconfig)
- [`PyCQA/bandit`](https://github.com/PyCQA/bandit)
- [`pypa/pipenv`](https://github.com/pypa/pipenv)
- [`pytorch/fairseq`](https://github.com/pytorch/fairseq)
- [`pytorch/serve`](https://github.com/pytorch/serve)
- [`pyupio/safety`](https://github.com/pyupio/safety)

#### R letter
- [`ralsina/rst-cheatsheet`](https://github.com/ralsina/rst-cheatsheet)
- [`random-forests/tutorials`](https://github.com/random-forests/tutorials)
- [`ranger/ranger`](https://github.com/ranger/ranger)
- [`rapidsai/spark-examples`](https://github.com/rapidsai/spark-examples)
- [`reiinakano/arbitrary-image-stylization-tfjs`](https://github.com/reiinakano/arbitrary-image-stylization-tfjs)
- [`rethinkdb/rethinkdb`](https://github.com/rethinkdb/rethinkdb)
- [`rgburke/grv`](https://github.com/rgburke/grv)
- [`RichardWarburton/java-8-lambdas-exercises`](https://github.com/RichardWarburton/java-8-lambdas-exercises)
- [`richzhang/colorization`](https://github.com/richzhang/colorization)
- [`riddhishb/ipython-notebooks`](https://github.com/riddhishb/ipython-notebooks)
- [`roaldnefs/awesome-prometheus`](https://github.com/roaldnefs/awesome-prometheus)
- [`robbie-cao/awesome-slides`](https://github.com/robbie-cao/awesome-slides)
- [`rofl0r/ncdu`](https://github.com/rofl0r/ncdu)
- [`rohitrango/automatic-watermark-detection`](https://github.com/rohitrango/automatic-watermark-detection)
- [`ropensci/wikitaxa`](https://github.com/ropensci/wikitaxa)
- [`rossant/awesome-math`](https://github.com/rossant/awesome-math)
- [`rough-stuff/wired-elements`](https://github.com/rough-stuff/wired-elements)
- [`Rudrabha/Lip2Wav`](https://github.com/Rudrabha/Lip2Wav)
- [`runatlantis/atlantis`](https://github.com/runatlantis/atlantis)
- [`ryanmcdermott/clean-code-javascript`](https://github.com/ryanmcdermott/clean-code-javascript)
- [`ryansmcgee/seirsplus`](https://github.com/ryansmcgee/seirsplus)
- [`salsita/node-pg-migrate`](https://github.com/salsita/node-pg-migrate)
- [`SamVerschueren/listr`](https://github.com/SamVerschueren/listr)
- [`santinic/how2`](https://github.com/santinic/how2)
- [`sapegin/shipit`](https://github.com/sapegin/shipit)
- [`sararob/ml-talk-demos`](https://github.com/sararob/ml-talk-demos)
- [`saulpw/visidata`](https://github.com/saulpw/visidata)
- [`sayakpaul/Data-Pipelines-with-TensorFlow-Data-Services-Exercises`](https://github.com/sayakpaul/Data-Pipelines-with-TensorFlow-Data-Services-Exercises)
- [`SBoudrias/Inquirer.js`](https://github.com/SBoudrias/Inquirer.js)
- [`sbt/junit-interface`](https://github.com/sbt/junit-interface)
- [`sbt/sbt-native-packager`](https://github.com/sbt/sbt-native-packager)
- [`sbt/sbt-pom-reader`](https://github.com/sbt/sbt-pom-reader)
- [`sbt/sbt-release`](https://github.com/sbt/sbt-release)
- [`sbt/sbt-site`](https://github.com/sbt/sbt-site)
- [`sbt/sbt-unidoc`](https://github.com/sbt/sbt-unidoc)
- [`scala-android/sbt-android`](https://github.com/scala-android/sbt-android)
- [`scala-exercises/exercises-stdlib`](https://github.com/scala-exercises/exercises-stdlib)
- [`scalacenter/scastie`](https://github.com/scalacenter/scastie)
- [`scalanlp/breeze`](https://github.com/scalanlp/breeze)
- [`scalatra/scalatra-in-action`](https://github.com/scalatra/scalatra-in-action)
- [`schibsted/strongbox`](https://github.com/schibsted/strongbox)
- [`Schmavery/facebook-chat-api`](https://github.com/Schmavery/facebook-chat-api)
- [`scoofy/wxStocks`](https://github.com/scoofy/wxStocks)
- [`ScorexFoundation/Scorex`](https://github.com/ScorexFoundation/Scorex)
- [`sebastianruder/NLP-progress`](https://github.com/sebastianruder/NLP-progress)
- [`segmentio/nightmare`](https://github.com/segmentio/nightmare)
- [`seratch/AWScala`](https://github.com/seratch/AWScala)
- [`sergiodxa/grial`](https://github.com/sergiodxa/grial)
- [`serialport/node-serialport`](https://github.com/serialport/node-serialport)
- [`serverless/examples`](https://github.com/serverless/examples)
- [`serverless/plugins`](https://github.com/serverless/plugins)
- [`serverless/serverless-graphql-blog`](https://github.com/serverless/serverless-graphql-blog)
- [`serverless/serverless`](https://github.com/serverless/serverless)
- [`sgratzl/slack_cleaner2`](https://github.com/sgratzl/slack_cleaner2)
- [`shadaj/slinky`](https://github.com/shadaj/slinky)
- [`sharetribe/sharetribe`](https://github.com/sharetribe/sharetribe)
- [`sharkdp/bat`](https://github.com/sharkdp/bat)
- [`sharkdp/fd`](https://github.com/sharkdp/fd)
- [`shelljs/shelljs`](https://github.com/shelljs/shelljs)
- [`Shopify/sarama`](https://github.com/Shopify/sarama)
- [`Siddharth11/Colorful`](https://github.com/Siddharth11/Colorful)
- [`simdjson/simdjson`](https://github.com/simdjson/simdjson)
- [`simeji/jid`](https://github.com/simeji/jid)
- [`simonepri/country-iso`](https://github.com/simonepri/country-iso)
- [`simonw/datasette`](https://github.com/simonw/datasette)
- [`SimulatedGREG/nginx-cheatsheet`](https://github.com/SimulatedGREG/nginx-cheatsheet)
- [`sindresorhus/awesome-electron`](https://github.com/sindresorhus/awesome-electron)
- [`sindresorhus/cli-spinners`](https://github.com/sindresorhus/cli-spinners)
- [`sindresorhus/eslint-plugin-unicorn`](https://github.com/sindresorhus/eslint-plugin-unicorn)
- [`sindresorhus/fkill-cli`](https://github.com/sindresorhus/fkill-cli)
- [`sindresorhus/macos-lock`](https://github.com/sindresorhus/macos-lock)
- [`sindresorhus/macos-trash`](https://github.com/sindresorhus/macos-trash)
- [`sindresorhus/on-change`](https://github.com/sindresorhus/on-change)
- [`sindresorhus/onetime`](https://github.com/sindresorhus/onetime)
- [`sindresorhus/pageres`](https://github.com/sindresorhus/pageres)
- [`sindresorhus/Plash`](https://github.com/sindresorhus/Plash)
- [`sindresorhus/refined-github`](https://github.com/sindresorhus/refined-github)
- [`sksamuel/avro4s`](https://github.com/sksamuel/avro4s)
- [`sksamuel/scrimage`](https://github.com/sksamuel/scrimage)
- [`snapcore/snapcraft`](https://github.com/snapcore/snapcraft)
- [`snowplow/iglu-central`](https://github.com/snowplow/iglu-central)
- [`SocialGouv/code-du-travail-numerique`](https://github.com/SocialGouv/code-du-travail-numerique)
- [`softwaremill/retry`](https://github.com/softwaremill/retry)
- [`softwaremill/sttp`](https://github.com/softwaremill/sttp)
- [`space10-community/conversational-form`](https://github.com/space10-community/conversational-form)
- [`spencermountain/compromise`](https://github.com/spencermountain/compromise)
- [`spencermountain/spacetime`](https://github.com/spencermountain/spacetime)
- [`spinnaker/spinnaker`](https://github.com/spinnaker/spinnaker)
- [`splicemachine/spliceengine`](https://github.com/splicemachine/spliceengine)
- [`sporto/awesome-elm`](https://github.com/sporto/awesome-elm)
- [`spotify/annoy`](https://github.com/spotify/annoy)
- [`spotify/apollo`](https://github.com/spotify/apollo)
- [`spotify/big-data-rosetta-code`](https://github.com/spotify/big-data-rosetta-code)
- [`spotify/featran`](https://github.com/spotify/featran)
- [`spotify/scio`](https://github.com/spotify/scio)
- [`spotify/styx`](https://github.com/spotify/styx)
- [`spotify/zoltar`](https://github.com/spotify/zoltar)
- [`spotty-cloud/spotty`](https://github.com/spotty-cloud/spotty)
- [`spring-projects/spring-boot`](https://github.com/spring-projects/spring-boot)
- [`sql-js/sql.js`](https://github.com/sql-js/sql.js)
- [`sqlpad/sqlpad`](https://github.com/sqlpad/sqlpad)
- [`sqreen/awesome-nodejs-projects`](https://github.com/sqreen/awesome-nodejs-projects)
- [`sryza/aas`](https://github.com/sryza/aas)
- [`sstephenson/bats`](https://github.com/sstephenson/bats)
- [`stan-dev/math`](https://github.com/stan-dev/math)
- [`statsd/statsd`](https://github.com/statsd/statsd)
- [`statsmodels/statsmodels`](https://github.com/statsmodels/statsmodels)
- [`stefanbuck/awesome-browser-extensions-for-github`](https://github.com/stefanbuck/awesome-browser-extensions-for-github)
- [`stimulusjs/stimulus`](https://github.com/stimulusjs/stimulus)
- [`STIXProject/python-stix`](https://github.com/STIXProject/python-stix)
- [`streamlit/streamlit`](https://github.com/streamlit/streamlit)
- [`stretchr/testify`](https://github.com/stretchr/testify)
- [`stripe/bonsai`](https://github.com/stripe/bonsai)
- [`stripe/dagon`](https://github.com/stripe/dagon)
- [`stripe/rainier`](https://github.com/stripe/rainier)
- [`substack/stream-handbook`](https://github.com/substack/stream-handbook)
- [`supermanue/example-library`](https://github.com/supermanue/example-library)
- [`superruzafa/visual-scala-reference`](https://github.com/superruzafa/visual-scala-reference)
- [`surveyjs/survey-library`](https://github.com/surveyjs/survey-library)
- [`swagger-api/swagger-codegen`](https://github.com/swagger-api/swagger-codegen)
- [`SwapnilSoni1999/spotify-dl`](https://github.com/SwapnilSoni1999/spotify-dl)

#### T letter
- [`tadhgfitzgerald/fifa_ranking`](https://github.com/tadhgfitzgerald/fifa_ranking)
- [`takari/maven-wrapper`](https://github.com/takari/maven-wrapper)
- [`takezoe/parallelizer`](https://github.com/takezoe/parallelizer)
- [`takezoe/picocli-scala-example`](https://github.com/takezoe/picocli-scala-example)
- [`taoufik07/responder`](https://github.com/taoufik07/responder)
- [`tats/w3m`](https://github.com/tats/w3m)
- [`techjacker/appsync-realtime-vanillajs`](https://github.com/techjacker/appsync-realtime-vanillajs)
- [`technosophos/moniker`](https://github.com/technosophos/moniker)
- [`tedyoung/awesome-java8`](https://github.com/tedyoung/awesome-java8)
- [`tensorflow/adanet`](https://github.com/tensorflow/adanet)
- [`tensorflow/docs`](https://github.com/tensorflow/docs)
- [`tensorflow/federated`](https://github.com/tensorflow/federated)
- [`tensorflow/graphics`](https://github.com/tensorflow/graphics)
- [`tensorflow/models`](https://github.com/tensorflow/models)
- [`tensorflow/playground`](https://github.com/tensorflow/playground)
- [`tensorflow/privacy`](https://github.com/tensorflow/privacy)
- [`tensorflow/serving`](https://github.com/tensorflow/serving)
- [`tensorflow/tensorflow`](https://github.com/tensorflow/tensorflow)
- [`tensorflow/tfjs-examples`](https://github.com/tensorflow/tfjs-examples)
- [`tensorflow/tfjs`](https://github.com/tensorflow/tfjs)
- [`tensorflow/tfx`](https://github.com/tensorflow/tfx)
- [`terryum/awesome-deep-learning-papers`](https://github.com/terryum/awesome-deep-learning-papers)
- [`thedevs-network/kutt`](https://github.com/thedevs-network/kutt)
- [`thekevinscott/ml-classifier-ui`](https://github.com/thekevinscott/ml-classifier-ui)
- [`ThilinaRajapakse/simpletransformers`](https://github.com/ThilinaRajapakse/simpletransformers)
- [`ThoughtWorksInc/Binding.scala`](https://github.com/ThoughtWorksInc/Binding.scala)
- [`ThoughtWorksInc/DeepLearning.scala`](https://github.com/ThoughtWorksInc/DeepLearning.scala)
- [`tiangolo/fastapi`](https://github.com/tiangolo/fastapi)
- [`timescale/timescaledb`](https://github.com/timescale/timescaledb)
- [`tj/node-prune`](https://github.com/tj/node-prune)
- [`tldr-pages/tldr`](https://github.com/tldr-pages/tldr)
- [`tmaiaroto/aegis`](https://github.com/tmaiaroto/aegis)
- [`tomazy/xcell`](https://github.com/tomazy/xcell)
- [`tombaranowicz/AmazonPricesMonitoring`](https://github.com/tombaranowicz/AmazonPricesMonitoring)
- [`tomnomnom/gron`](https://github.com/tomnomnom/gron)
- [`tomslee/airbnb-data-collection`](https://github.com/tomslee/airbnb-data-collection)
- [`toniov/gcal-cli`](https://github.com/toniov/gcal-cli)
- [`tpolecat/doobie`](https://github.com/tpolecat/doobie)
- [`tpolecat/tut`](https://github.com/tpolecat/tut)
- [`transcendent-ai-labs/DynaML`](https://github.com/transcendent-ai-labs/DynaML)
- [`transitive-bullshit/awesome-ffmpeg`](https://github.com/transitive-bullshit/awesome-ffmpeg)
- [`traviscross/mtr`](https://github.com/traviscross/mtr)
- [`trimstray/test-your-sysadmin-skills`](https://github.com/trimstray/test-your-sysadmin-skills)
- [`triplequote/sbt-scalabench`](https://github.com/triplequote/sbt-scalabench)
- [`trufflesuite/truffle`](https://github.com/trufflesuite/truffle)
- [`tsenart/vegeta`](https://github.com/tsenart/vegeta)
- [`tstack/lnav`](https://github.com/tstack/lnav)
- [`tum-vision/fastms`](https://github.com/tum-vision/fastms)
- [`tupleblog/face-classification-js`](https://github.com/tupleblog/face-classification-js)
- [`Turfjs/turf`](https://github.com/Turfjs/turf)
- [`twitter/bijection`](https://github.com/twitter/bijection)
- [`twosigma/flint`](https://github.com/twosigma/flint)
- [`TylerBrock/saw`](https://github.com/TylerBrock/saw)
- [`typelevel/spire`](https://github.com/typelevel/spire)
- [`typelevel/squants`](https://github.com/typelevel/squants)
- [`typicode/json-server`](https://github.com/typicode/json-server)
- [`tzutalin/labelImg`](https://github.com/tzutalin/labelImg)
- [`uber/ludwig`](https://github.com/uber/ludwig)
- [`underscoreio/shapeless-guide`](https://github.com/underscoreio/shapeless-guide)
- [`Unitech/pm2`](https://github.com/Unitech/pm2)
- [`Unity-Technologies/unitysimulation-coronavirus-example`](https://github.com/Unity-Technologies/unitysimulation-coronavirus-example)
- [`uNmAnNeR/imaskjs`](https://github.com/uNmAnNeR/imaskjs)
- [`usefathom/fathom`](https://github.com/usefathom/fathom)

#### V letter
- [`validatorjs/validator.js`](https://github.com/validatorjs/validator.js)
- [`valyala/fasthttp`](https://github.com/valyala/fasthttp)
- [`VBA-tools/VBA-Web`](https://github.com/VBA-tools/VBA-Web)
- [`vega/vega-lite`](https://github.com/vega/vega-lite)
- [`vegas-viz/Vegas`](https://github.com/vegas-viz/Vegas)
- [`vercel/hyper`](https://github.com/vercel/hyper)
- [`vercel/micro`](https://github.com/vercel/micro)
- [`vercel/vercel`](https://github.com/vercel/vercel)
- [`verekia/js-stack-from-scratch`](https://github.com/verekia/js-stack-from-scratch)
- [`victordibia/handtrack.js`](https://github.com/victordibia/handtrack.js)
- [`vim-syntastic/syntastic`](https://github.com/vim-syntastic/syntastic)
- [`visgl/loaders.gl`](https://github.com/visgl/loaders.gl)
- [`vkostyukov/scalacaster`](https://github.com/vkostyukov/scalacaster)
- [`vuejs/awesome-vue`](https://github.com/vuejs/awesome-vue)
- [`wagoodman/dive`](https://github.com/wagoodman/dive)
- [`wallabag/wallabag`](https://github.com/wallabag/wallabag)
- [`wallix/awless`](https://github.com/wallix/awless)
- [`wangzheallen/awesome-human-pose-estimation`](https://github.com/wangzheallen/awesome-human-pose-estimation)
- [`wartremover/wartremover`](https://github.com/wartremover/wartremover)
- [`watsonbox/exportify`](https://github.com/watsonbox/exportify)
- [`wavexx/screenkey`](https://github.com/wavexx/screenkey)
- [`wg/wrk`](https://github.com/wg/wrk)
- [`wilfredinni/python-cheatsheet`](https://github.com/wilfredinni/python-cheatsheet)
- [`williamngan/pts`](https://github.com/williamngan/pts)
- [`WillKoehrsen/Bokeh-Python-Visualization`](https://github.com/WillKoehrsen/Bokeh-Python-Visualization)
- [`winitzki/sofp`](https://github.com/winitzki/sofp)
- [`wooorm/franc`](https://github.com/wooorm/franc)
- [`wtfutil/wtf`](https://github.com/wtfutil/wtf)
- [`wting/autojump`](https://github.com/wting/autojump)
- [`wvlet/airframe`](https://github.com/wvlet/airframe)
- [`xbpeng/DeepMimic`](https://github.com/xbpeng/DeepMimic)
- [`xdotai/diff`](https://github.com/xdotai/diff)
- [`xmlking/nifi-examples`](https://github.com/xmlking/nifi-examples)
- [`xtermjs/xterm.js`](https://github.com/xtermjs/xterm.js)
- [`Y2Z/monolith`](https://github.com/Y2Z/monolith)
- [`yahoo/open_nsfw`](https://github.com/yahoo/open_nsfw)
- [`yai333/pythonserverlesssample`](https://github.com/yai333/pythonserverlesssample)
- [`Yomguithereal/mnemonist`](https://github.com/Yomguithereal/mnemonist)
- [`you-dont-need/You-Dont-Need-Momentjs`](https://github.com/you-dont-need/You-Dont-Need-Momentjs)
- [`yudai/gotty`](https://github.com/yudai/gotty)
- [`z-pattern-matching/z`](https://github.com/z-pattern-matching/z)
- [`zalando/tech-radar`](https://github.com/zalando/tech-radar)
- [`zalandoresearch/fashion-mnist`](https://github.com/zalandoresearch/fashion-mnist)
- [`zenazn/goji`](https://github.com/zenazn/goji)
- [`ziishaned/dumper.js`](https://github.com/ziishaned/dumper.js)
- [`zotero/zotero`](https://github.com/zotero/zotero)
- [`zricethezav/gitleaks`](https://github.com/zricethezav/gitleaks)

### References
[back to TOC](#table-of-contents)

- https://www.goodreads.com/api/index#shelves.list
- https://api.github.com/users/mycaule/starred?page=9&per_page=100
- https://getpocket.com/developer/docs/v3/retrieve
