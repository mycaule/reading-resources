## Big reading log

Some useful pointers for Software engineers. Collected over 10 years in the software industry.

### Why?

- To keep track of helpful resources I have referred to during my career
- To help my fellow young colleagues learn quickly

<center><img src="images/elephant.png" width=250/></center>

Inspiration: [Richard Stallman](https://stallman.org), [Jason Kottke](https://www.kottke.org), [Sindre Sohrus](https://sindresorhus.com), [Stephen Wolfram](https://www.wired.com/2012/03/opinion-wolfram-life-analytics/), [Mari Kondo](https://konmari.com), [Leo Babauta](https://leobabauta.com)

------------------------------

### Table of Contents

- [Posts](#posts-and-webapps)
  - [2023](#2023) | [2022](#2022) | [2021](#2021)
  - [2020](#2020) | [2019](#2019) | [2018](#2018) | [2017](#2017) | [2016](#2016)
  - [2015](#2015) | [2014](#2014) | [2013](#2013) | [2012](#2012) | [2011](#2011)
- [Books](#books)
- [Blogs](#blogs-and-podcasts)
  - [Following](#following) | [Social Networks](#social-networks) | [Archive](#archive)
- [Newsletters](#newsletters)
- [Online courses](#online-courses)
- [Repositories](#repos-toolbox-for-work-related-problems)
  - [CSS](#css) | [Prompt](#prompt) | [Node.js](#javascript) | [Scala](#scala) | [Java](#java)
  - [Python](#python) | [Go](#go-and-native-languages) | [CLI](#cli) | [DevOps](#devops) | [Security](#security)
- [Quotes](#quotes)

------------------------------

### About Me

[About me](https://gist.github.com/mycaule/636203b3f8f4a9c5eb91f397a63b3e22), [Curriculum vitae](https://www.linkedin.com/in/michelhua/).

Some talks I have done recently, mostly in French: [A short history of the software industry](https://gist.github.com/mycaule/39356443c267c0743253282044da16c0), [Productivity tips and decluttering](https://gist.github.com/mycaule/d2f3bc69747aef7f550d2bcc80ec4e63), [Deep learning for programmers](https://gist.github.com/mycaule/1776ed63d059eee92d86976e8f399f69)

Subjects I am researching about: [3D Pose applications](https://gist.github.com/mycaule/070965966d39d3ae5cd1b2fb86fe92ff), [Data journalism](https://gist.github.com/mycaule/883f01c67cb6be5112fe25408016517a), technical writing and editing. My past [micro-entrepreurial ideas](https://gist.github.com/mycaule/886aa10c08d68e4f85bfa49e5456f92e).

### Posts and Webapps

[back to TOC](#table-of-contents)

#### 2023

##### Objectives

- Write a small project in Go language using one of [the libraries below](#go-and-other-hot-languages)
- Write part of a book using [RMarkdown](https://bookdown.org/yihui/rmarkdown/tufte-handouts.html) or [mdBook](https://github.com/rust-lang/mdBook)
- Exciting things: [Mediapipe](https://mediapipe.dev), [Roboflow](https://www.roboflow.com), [Idyll](https://idyll-lang.org/), [Julia](https://julialang.org)

##### March

- Microsoft [continues investing in OpenAI](https://www.bloomberg.com/news/articles/2023-03-13/microsoft-built-an-expensive-supercomputer-to-power-openai-s-chatgpt) promising to innovate using transformers in the [enterprise applications](https://news.microsoft.com/source/features/ai/how-microsofts-bet-on-azure-unlocked-an-ai-revolution/). Developers can already try to build their own apps using GPT-3, Codex, and with [Spark plugins](https://github.com/microsoft/SynapseML/blob/master/notebooks/features/cognitive_services/CognitiveServices%20-%20OpenAI.ipynb) already available. On the desktop side, Microsoft Teams already integrates with ChatGPT.
- In [GPT-3 and Beyond](https://www.youtube.com/watch?v=-lnHHWRCDGk), Christopher Potts explains how algorithms are outperforming humans in classic NLP problems with the dimensionality explosion of large language models (LLM).
- In a [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide), authors from `dair.ai` dissect how prompt works in LLM. Ironically, the term "prompt engineer" also begins to pop up as a newly demanded skill on LinkedIn promising to change the way we work.
- YOLOv8 was [released in January 2023](https://blog.roboflow.com/whats-new-in-yolov8/), this short tutorial video explains how to easily train a object detection system using popular service [Roboflow](https://www.youtube.com/watch?v=wuZtUMEiKWY), which supports multiple deployment platform, web or on even edge devices from Nvidia and Luxonis.
- Inside [Zillow's propensity model](http://www.zillow.com/tech/identifying-high-intent-buyers). Authors explain how the real estate platform identify potential buyers and serve them the appropriate contents.
- A walkthough on how to build a [embeddings based similar products](https://redis.com/blog/real-time-product-recommendation-docarray/) recommendation system using Redis and Docarray.
- Choosing between [Snowflake, Databricks, BigQuery or Redshift or EMR](https://lakshmanok.medium.com/snowflake-or-databricks-bigquery-or-dataproc-redshift-or-emr-e40190c97ef8) from Lak Lakshmanan, using [Apache Iceberg from your data lakehouse](https://overcast.fm/+H1YNxomXg/29:24?utm_source=pocket_saves)


##### January

- A primer from PagerDuty for dealing with technical incidents. The [Postmortem document](https://postmortems.pagerduty.com/meeting/) is at the core of the SRE culture, making sure the process is clear will make engineering teams succeed, when facing critical applications and busy stakeholders. PagerDuty is a [SaaS service](https://www.pagerduty.com/) to provide engineer tools to manage on-calls effectively.
- Guido van Rossum, creator of Python language, was invited at the Lex Fridman Podcast for the second time. He shared his opinions about [the language evolution](https://www.youtube.com/watch?v=-DVyjdw4t9I), [programmer careers](https://www.youtube.com/watch?v=-DVyjdw4t9I&t=10571s), but also new things like GitHub Copilot which he says [he uses personally](https://www.youtube.com/watch?v=-DVyjdw4t9I&t=10963s).
- 10 years after the [foundational article](https://hbr.org/2012/10/data-scientist-the-sexiest-job-of-the-21st-century) from Harvard Business Review, the [original authors talk about the evolutions](https://hbr.org/2022/07/is-data-scientist-still-the-sexiest-job-of-the-21st-century) of opportunity in data science related careers. They discuss how this new area played a big role in maintaining companies stability and growth, highlight the challenges to train or find skillful people, and also the new trends of MLOps.
- GCP provides a [40 points checklist](https://cloud.google.com/blog/products/data-analytics/optimize-cloud-composer-via-better-airflow-dags/) to maintain a well-organized Airflow code base.
- Following a recent refactoring, LinkedIn wrote a [comprehensive architecture note](https://engineering.linkedin.com/blog/2023/unifying-messaging-experiences-across-linkedin) about how their central instant messaging component works, enabling its 900 million members to communicate in real time.
- Snowflake [released new features](https://www.snowflake.com/blog/category/product-and-technology/release-notes/) possibility with some security enhancements and the possibility to run query from VSCode.

#### 2022

##### December

- [GitHub tips to level up your CI/CD](https://github.blog/2022-07-19-6-strategic-ways-to-level-up-your-ci-cd-pipeline/)
- With new GPT-3 type models capable of generating human like contents and even [winning arts competition](https://www.washingtonpost.com/technology/2022/09/02/midjourney-artificial-intelligence-state-fair-colorado/), [a16z is considering how](https://future.com/how-to-build-gpt-3-for-science/) it can extend to other area such as science, and potentially change how researchers work.
- In research conducted end of 2021, McKinsey identified major AI opportunities for China. Key sectors of automotive, manufacturing and enterprise software could [bring up to $600 billion](https://www.mckinsey.com/business-functions/quantumblack/our-insights/the-next-frontier-for-ai-in-china-could-add-600-billion-to-its-economy) to using AI technologies.
- In mind sports and online games, [professional have been using AI](https://www.washingtonpost.com/business/magnus-carlsens-strongest-chess-opponentis-ai/2022/09/13/0c43cd10-3379-11ed-a0d6-415299bfebd5_story.html) to cheat and win prizes. A controversy has been going on in September involving top players for the game of chess. The columnist also prospects that people in the future will be using AI wearables for everyday decisions.
- AWS [unveiled a report](https://pages.awscloud.com/rs/112-TZM-766/images/Etude_de_l_impact_economique_d_AWS.pdf) on the economic impact of AWS in France. The group plans to invest 5 billion between 2022 and 2031. It also highlights that France is lagging behind in the training of data profiles. AWS will also adopt a sustainability approach through the use of less energy consuming ARM chips.
- AlphaTensor, an AI developed by based on previous work AlphaZero, has solved an old numerical analysis problem. The system was trained to [search efficient matrix multiplication algorithms](https://www.deepmind.com/blog/discovering-novel-algorithms-with-alphatensor) and outperformed Strassen algorithm.
- During this year's Ignite event ([day1](https://www.linkedin.com/video/event/urn:li:ugcPost:6978828296645980160/), [day2](https://www.linkedin.com/video/event/urn:li:ugcPost:6980293452466982912/)). Microsoft announced changes on the server side, like ARM-based instances, AI assistance for developers, but also for corporate meetings, and an upgrade of Azure OpenAI. On the desktop side, Windows 11 updates and Microsoft Teams updates should improve the quality of the calls. [TLDR note from Satya Nadella](https://www.linkedin.com/pulse/doing-more-less-microsoft-cloud-satya-nadella/)
- Laptops and desktop computers are more powerful than ever. [Now with DuckDB](https://duckdb.org/why_duckdb), a new in-memory OLAP tool, developers can take use their own compute power. Horizontal scaling is no longer necessary for simple analyses.
- Different types of senior level engineers are depicted in this article with [their typical weekly schedule](https://staffeng.com/guides/staff-archetypes). Interesting ideas of how developers can organize their time to be more focused and productive.
- Meta recently opened an API to write [chatbots for the WhatsApp messaging platform](https://developers.facebook.com/blog/post/2022/10/24/sending-messages-with-whatsapp-in-your-python-applications/). With a backend server in Python, [Flask](https://github.com/pallets/flask) or [FastAPI](https://github.com/tiangolo/fastapi) for example, businesses can now trigger text events enriched with ML or API calls, or retrieve knowledge from an external source. With chatbots, brands can engage their users in a direct and personalized way, using a simple text interface, and [Facebook has been one of the first platforms](https://developers.facebook.com/blog/post/2016/04/12/bots-for-messenger/) to enable business and developers to do it.

##### October

- https://github.com/openai/whisper
- https://snyk.io/blog/best-practices-create-modern-npm-package
- https://duckdb.org/2022/10/12/modern-data-stack-in-a-box.html
- https://www.linkedin.com/pulse/doing-more-less-microsoft-cloud-satya-nadella
- https://www.deepmind.com/blog/discovering-novel-algorithms-with-alphatensor

##### June

- DVC released a new [ML extension](https://dvc.org/blog/DVC-VS-Code-extension) to track both experiments and datasets directly with Git and VS Code, check out this [demo](https://www.youtube.com/watch?v=Eq3100S3aHw) on YouTube.
- Amazon recently released code with a [minimalistic infrastructure](https://aws-quickstart.github.io/quickstart-amazon-marketing-cloud/) to process its Marketing Cloud API.
- Google broke the world record for computing the Pi number digits, they provided a small [API](https://pi.delivery/) for developers to try out and [discussed the infrastructure](https://cloud.google.com/blog/products/compute/calculating-100-trillion-digits-of-pi-on-google-cloud) they used for this classical HPC workload.

##### May

- How Spotify performs similarity search for their podcasts, using [Tensorflow, Vertex AI and Vespa](https://engineering.atspotify.com/2022/03/introducing-natural-language-search-for-podcast-episodes/)
- Twitter following Spotify to move more of its data infrastructure to [managed services on GCP](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2022/scaling-data-access-by-moving-an-exabyte-of-data-to-google-cloud)

##### March

- dbt's article about [analytics enginering](https://www.getdbt.com/what-is-analytics-engineering/) and [new courses](https://blog.getdbt.com/new-learn-courses/)
- The challenges of serving neural networks in production, how [small businesses can reuse pre-trained models or APIs](https://future.a16z.com/ai-ml-foundation-models-for-the-rest-of-us/)

##### January

- Avocode [templates](https://www.notion.so/Shape-Up-template-by-Avocode-9478361c11c64a5ebe83abe74e39f9b8) to apply the Shape Up method

#### 2021
[back to TOC](#table-of-contents)

##### December

- Li Haoyi's [tips on publishing a technical book](https://www.lihaoyi.com/post/HowISelfPublishedMyFirstTechnicalBook.html)

##### June

- [Data Cloud Summit - How CDC Can Improve Your Life](https://www.youtube.com/watch?v=3txIn-XYPGY)
- [Use SRE principles to monitor pipelines with Cloud Monitoring dashboards](https://cloud.google.com/blog/products/management-tools/the-right-metrics-to-monitor-cloud-data-pipelines)

##### May

- [How to replay time series data from BigQuery to Pub/Sub](https://medium.com/google-cloud/how-to-replay-time-series-data-from-google-bigquery-to-pub-sub-c0a80095124b)
- [Data Mesh Principles and Logical Architecture](https://martinfowler.com/articles/data-mesh-principles.html)
- [Keyword reference for the .gitlab-ci.yml file](https://docs.gitlab.com/ee/ci/yaml/README.html)
- [Oracle to BigQuery migration guide](https://cloud.google.com/architecture/dw2bq/oracle/oracle-bq-migration-guide), chapter on data migration has interesting information on CDC with Oracle
- [CDC with Datastream](https://cloud.google.com/blog/products/databases/new-cloud-based-cdc-replication-across-databases), [Datastream to BigQuery code samples](https://github.com/GoogleCloudPlatform/DataflowTemplates/tree/master/v2/datastream-to-bigquery)

##### April

- [Incremental models on BigQuery with dbt](https://youtu.be/UUuvMvPD9iA?t=1950)
- [Dataform incremental datasets](https://docs.dataform.co/guides/datasets/incremental#a-merge-example)

##### March

- [Performing ETL from a relational database into BigQuery using Dataflow](https://cloud.google.com/solutions/performing-etl-from-relational-database-into-bigquery)
- [Change Data Capture from MySQL to BigQuery using Debezium and Pub/Sub (Stream)](https://cloud.google.com/dataflow/docs/guides/templates/provided-streaming#change-data-capture)
- [GCP Icons](https://cloud.google.com/icons/files/google-cloud-platform-official-icons-and-sample-diagrams.pptx)
- [Gitlab CI/CD documentation](https://docs.gitlab.com/ee/ci/README.html)
- [Getting table metadata using INFORMATION_SCHEMA](https://cloud.google.com/bigquery/docs/information-schema-tables)

##### January
- CNIL resources: [Opt-out design patterns](https://design.cnil.fr/concepts/), [GDPR for developers](https://lincnil.github.io/Guide-RGPD-du-developpeur/), [remote working tips](https://lincnil.github.io/Recommandations-pour-le-teletravail/) this one also provides some interesting links of ANSSI and Minister of Interior best practices
- [Google research](https://ai.googleblog.com/2021/01/google-research-looking-back-at-2020.html) review of 2020.
- [The Guardian's data science blog](https://www.theguardian.com/data)
- [Using BigTable with Dataflow at Spotify](https://www.youtube.com/watch?v=807uHC0Ia10)
- [Full stack Deep learning](https://course.fullstackdeeplearning.com) course, includes a full lab on [handwritten text recognition](https://www.youtube.com/playlist?list=PL1T8fO7ArWlfx84Kc1Ke4a3DTGAzwnApV)

------------------------------

#### 2020
[back to TOC](#table-of-contents)

##### December
- [Google Analytics academy](https://analytics.google.com/analytics/academy/) online course to keep on track with Google Analytics
- [PlantUML](https://plantuml.com) uses good old UML, I use it at my company [for documentation](https://github.com/mycaule/shape-up-plant-uml/), it also provides a nice [plugin for VSCode](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml)
- [Slack Deletron](https://slackdeletron.com)
- [Tips on how to secure](https://github.com/forter/security-101-for-saas-startups/blob/english/security.md) your company quickly and the [MITRE Attack](https://attack.mitre.org) framework
- Great post on how to do [code reviews the right way](https://mtlynch.io/code-review-love/)
- [Financial Times - Visual Vocabulary](https://raw.githubusercontent.com/ft-interactive/chart-doctor/master/visual-vocabulary/poster.png)
- [Color Lisa](http://www.colorlisa.com/) has palettes from great designers

##### November
- [Open Fisca](https://openfisca.org/fr), [Etalab repository](https://github.com/etalab) and [Github for governments](https://government.github.com/community/) has plenty of resources for checking open source governmental algorithms
- Deepmind : one documentary on [AlphaGo](https://www.youtube.com/watch?v=WXuK6gekU1Y), Lex Fridman about the advances of [Alphafold2](https://www.youtube.com/watch?v=W7wJDJ56c88)
- [French government typography](https://www.gouvernement.fr/charte/charte-graphique-les-fondamentaux/la-typographie)
- [BigQuery book](https://www.goodreads.com/book/show/50204627-google-bigquery), [cheatsheet for window functions](https://datarunsdeep.com.au/blog/cool-things-you-can-do-using-window-functions-bigquery)
- [dbt](https://www.getdbt.com) is a cool modern tool to manage datawarehouse pipelines saving nights of headaches
- a16z [emerging data architectures](https://a16z.com/2020/10/15/the-emerging-architectures-for-modern-data-infrastructure/)
- Hacking an API to check if [the McDonald's ice cream machine broken?](https://kottke.org/20/10/is-the-mcdonalds-ice-cream-machine-broken)

##### July
- [`GoogleCloudPlatform/mlops-on-gcp/`](https://github.com/GoogleCloudPlatform/mlops-on-gcp/tree/master/workshops/) has sample bootstrap project of using Kubeflow Pipelines and Argo Workflow. See also [YouTube cast](https://www.youtube.com/watch?v=qx7MLcbCo5g) and the [Pipelines SDK](https://www.kubeflow.org/docs/pipelines/sdk/sdk-overview/)
- [Srini Devadas and Erik Demaine @ MIT 2011 - Introduction to algorithms](https://www.youtube.com/playlist?list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb) focuses in general ideas rather than the details. One can refer to [Thomas Cormen et al. book](https://www.goodreads.com/book/show/108986.Introduction_to_Algorithms) for a comprehensive list of modern algorithms.
- [Github actions documentation](https://help.github.com/en/actions): is now very mature can help automate some of the things I collected on GitHub and replace old CI systems. Especially it can be used for [ML operations](https://github.blog/2020-06-17-using-github-actions-for-mlops-data-science/) see [YouTube cast](https://www.youtube.com/watch?v=Ll50l3fsoYs) and [`actions-ml-cicd`](https://github.com/machine-learning-apps/actions-ml-cicd)
- [Architecting with Google Kubernetes Engine Specialization](https://www.coursera.org/specializations/architecting-google-kubernetes-engine) covers all the aspects of using Kubernetes in a professional context, has plenty of hands-on labs and code samples to practice.

##### April

- Corey Schafer video tutorials on Python subjects [Pandas](https://www.youtube.com/playlist?list=PL-osiE80TeTsWmV9i9c58mdDCSskIFdDS), [Matplotlib](https://www.youtube.com/playlist?list=PL-osiE80TeTvipOqomVEeZ1HRrcEvtZB_)
- [James Powell talks at PyData](https://www.youtube.com/watch?v=cKPlPJyQrt4&list=PLJsotIV0ZEQDpIIKhT-33qU1WEefRRrBL) highlights some of the powerful specifics of Python 3, decorators, context managers etc.
- French research labs INRIA also have interesting courses on techniques they use in biostatistics [Recherche reproductible](https://www.fun-mooc.fr/courses/course-v1:inria+41016+self-paced/info), [Python 3](https://www.fun-mooc.fr/courses/course-v1:UCA+107001+session02/info) emphases research versus software engineering
- [Covid datapack by InformationIsBeautiful](https://informationisbeautiful.net/visualizations/covid-19-coronavirus-infographic-datapack/)

##### March
- [Stéphane Mallat @ Collège de France - Modèles multi-échelles et réseaux de neurones convolutifs](https://www.college-de-france.fr/site/stephane-mallat/course-2019-2020.htm): third consecutive year of expert class to be held weekly about Deep Learning
- [Deep Learning courses @ MIT 2020](https://deeplearning.mit.edu/), the introduction course State of the Art is the most interesting one every year
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

------------------------------

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
- [Chrome Extension - URL Rewriter](https://chrome.google.com/webstore/detail/url-rewriter/gpbblpbcnjdnnjdcdclojoonfmpoionh) lets you rewirte `^(http[s]?\:\/\/)(en\.)(wikipedia\.org.*)$` to replace group number 2 by `en.m.`
- Inspiring open source initiatives: [Deezer](https://deezer.io/releasing-spleeter-deezer-r-d-source-separation-engine-2b88985e797e), [Google Jigsaw](https://medium.com/the-false-positive/creating-labeled-datasets-and-exploring-the-role-of-human-raters-56367b6db298)

##### September
- [Pierre Courtiol @ Collège de France - S'attaquer à une compétition de machine learning](https://www.college-de-france.fr/site/stephane-mallat/seminar-2018-02-21-11h15.htm) about tricks to make models perform better and win Kaggle competitions
- [NHK World - 10 Years with Hayao Miyazaki](https://www3.nhk.or.jp/nhkworld/en/ondemand/program/video/10yearshayaomiyazaki/)
- [Data journalism handbook](https://datajournalismhandbook.net/)

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
- [Building Scala libraries](https://guides.gradle.org/building-scala-libraries/) with Gradle

------------------------------

#### 2018
[back to TOC](#table-of-contents)

##### December
- [AWS Labs - SageMaker examples](https://github.com/awslabs/amazon-sagemaker-examples)
- [Google Dataset Search](https://toolbox.google.com/datasetsearch)
- [Google Research - Seedbank](https://research.google.com/seedbank/)
- Useful notes for Spark: [Tips to Debug Apache Spark](https://databricks.com/blog/2016/10/18/7-tips-to-debug-apache-spark-code-faster-with-databricks.html), [Apache Spark Visualization](https://databricks.com/blog/2015/06/22/understanding-your-spark-application-through-visualization.html), [Submitting User Applications with `spark-submit`](https://aws.amazon.com/fr/blogs/big-data/submitting-user-applications-with-spark-submit/), [Managing memory for Apache Spark](https://aws.amazon.com/fr/blogs/big-data/best-practices-for-successfully-managing-memory-for-apache-spark-applications-on-amazon-emr/), [`ammonite-spark` EMR tutorial](https://gist.github.com/alexarchambault/8e1eec124f00b1c5576a29899ae39569)
- [Black hole computer simulations](https://kottke.org/18/12/computer-simulations-of-black-hole-mergers-observed-by-ligo)

##### August
- Spotify Engineering Culture ([part1](https://engineering.atspotify.com/2014/03/27/spotify-engineering-culture-part-1/), [part2](https://engineering.atspotify.com/2014/09/20/spotify-engineering-culture-part-2/))
- [EC2 Instances](https://www.ec2instances.info/)
- [The beauty of constraints in engineering](https://kottke.org/18/06/the-beauty-of-constraints-in-engineering)
- Learning Spark with [Coursera](https://www.coursera.org/learn/scala-spark-big-data) and [Heather Miller](https://heather.miller.am/blog/launching-a-spark-cluster-part-2.html)
- [Command line fu](https://www.commandlinefu.com/commands/matching/aws/YXdz/sort-by-votes)

##### March
- [John Bates, Anthony Joseph - Data Science and Engineering with Spark](https://www.edx.org/xseries/data-science-engineering-apacher-sparktm)
- [Martin Odersky, Heather Miller - Functional programming in Scala Specialization](https://www.coursera.org/specializations/scala)
- [Heather Miller - Distributed Programming](http://dist-prog-book.com/chapter/1/rpc.html)
- Some Scala resources: [Alvin Alexander - Scala cookbook](https://alvinalexander.com/scala), , [47 Degrees - Scala exercises](https://www.scala-exercises.org/), [Homegrown Scala collections](https://www.youtube.com/playlist?list%3DPLJGDHERh23x-4bTASKbtwhhAuP6rYQJqE)
- Playing with Spark EMR and Zeppelin, [Spark SQL Partition discovery](https://spark.apache.org/docs/2.3.1/sql-programming-guide.html%23partition-discovery), [AWS EMR releases](https://docs.aws.amazon.com/en_en/emr/latest/ReleaseGuide/emr-release-5x.html), [gallery of Zeppelin Notebooks](https://github.com/hortonworks-gallery/zeppelin-notebooks)

##### January
- [Kelsey Hightower, Carter Morgan - Scalable microservices](https://eu.udacity.com/course/scalable-microservices-with-kubernetes--ud615)
- Resources for using Nginx: [Diego Plentz - Nginx configuration for improved security and performance](https://gist.github.com/plentz/6737338), [awesome Nginx](https://github.com/agile6v/awesome-nginx)

------------------------------

#### 2017
[back to TOC](#table-of-contents)

##### December
- [Joshua Thijssen - REST Cookbook](http://restcookbook.com/)
- [OWASP Foundation - OWASP Top 10](https://www.owasp.org/images/7/72/OWASP_Top_10-2017_%2528en%2529.pdf.pdf)
- [Andrew Ng - Machine learning](https://www.coursera.org/learn/machine-learning)
- [Jerome Friedman - The Elements of Statistical Learning](https://web.stanford.edu/~hastie/Papers/ESLII.pdf)
- [Amy Brown - The architecture of open source applications](https://aosabook.org/en/)

##### March
- [AWS Whitepapers](https://aws.amazon.com/fr/whitepapers/)
- [Franz](https://meetfranz.com/)
- [Postman](https://www.getpostman.com/)
- https://students.brown.edu/seeing-theory/, March 2017

------------------------------

#### 2016
[back to TOC](#table-of-contents)

##### December
- [Kevin van Zonneveld - Bash best practices](https://kvz.io/bash-best-practices.html)
- Paulo Coelho [advices for entrepreneurs](https://paulocoelhoblog.com/2016/11/30/10-success-lessons-from-paulo-coelho-the-alchemist-for-entrepreneurs/)

##### June
- [Vincent Driessen - A successful Git branching model](https://nvie.com/posts/a-successful-git-branching-model/)
- [Peter Cottle - Learn git branching](https://learngitbranching.js.org)
- [CSS from the future](https://zeke.sikelianos.com/css-from-the-future/)
- [Twitter's effective Scala](https://twitter.github.io/effectivescala/) guidelines

##### March
- [Scala Exercises](https://www.scala-exercises.org/) is a good website to learn Scala interactively.
- [Tails](https://tails.boum.org/) is a USB operating system to preserve privacy.

##### January
- [Jonathan Boyer - Comprendre Git](https://www.grafikart.fr/formations/git)
- https://navitia.io/

------------------------------

#### 2015
[back to TOC](#table-of-contents)

- Node.js resources: [nodejs.org](http://nodejs.org/), [Lodash](http://lodash.com/), [Passport](http://passportjs.org/)
- [Twitter Bootstrap](http://getbootstrap.com/)
- Drawing diagrams with [ASCII Flow](http://asciiflow.com/) and [Web Sequence Diagrams](https://www.websequencediagrams.com/)
- French blog post with all [the passenger information designs](http://sncfunepassionquisepartage.weebly.com/reacuteseau-sncf.html), very cool
- David Graeber [post on "bullshit jobs"](https://www.strikemag.org/bullshit-jobs/)
- [AWS Architecture center](https://aws.amazon.com/architecture/)
- [Firebase](https://www.firebase.com/docs/)
- [10 Things Paul Irish learned from the jQuery source](https://vimeo.com/12529436)
- [PowerShell and Bash compared](http://xahlee.info/powershell/PowerShell_for_unixer.html), [UNIX for DOS users](http://www.yolinux.com/TUTORIALS/unix_for_dos_users.html)
- [Made How, How products are made](http://www.madehow.com)
- How Microsoft's [How Old robot](https://how-old.net/themagic) works
- [Achemine](https://brunobernard.com/work/achemine/), SNCF font in train stations
- According to CNRS, [Maths are doping the French economy](https://lejournal.cnrs.fr/articles/les-maths-dopent-leconomie-francaise)

##### September
- [Marvel](https://marvelapp.com/), [Invision](https://www.invisionapp.com/)
- [What's the Go language really good for](https://www.infoworld.com/article/2928602/google-go/whats-the-go-language-really-good-for.html)

##### March
- [The Twelve-Factor App](https://12factor.net/)
- https://www.bbc.co.uk/blogs/internet/entries/47a96d23-ae04-444e-808f-678e6809765d, March 2015
- [Elevator Saga](https://play.elevatorsaga.com/) for learning JavaScript

------------------------------

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
- [W3Schools](http://www.w3schools.com/) gave me the basics of modern web layout, I was also interested in colorwheels [1](http://www.sessions.edu/color-calculator), [2](http://www.colorschemer.com/online.html) and JavaScript, [How jQuery works](https://learn.jquery.com/about-jquery/how-jquery-works/)
- [Secure share](https://securesha.re/) interesting 0-server file-sharing website
- [Learn you a Haskell](http://learnyouahaskell.com/modules), one colleague told me about Haskell, "it is like maths you will like it".
- [enable cross-origin resource sharing](https://enable-cors.org/)
- [Inside DuckDuckGo](https://www.fastcompany.com/3026698/inside-duckduckgo-googles-tiniest-fiercest-competitor)
- Resources for learning MongoDB: https://university.mongodb.com/, https://cookbook.mongodb.org/
- https://datatables.net/
- [AWS vs GCP](https://qz.com/196819/how-amazon-beat-google-attempt-to-dominate-the-cloud-before-it-even-got-started/)
- https://learnvimscriptthehardway.stevelosh.com/

------------------------------

#### 2013

[back to TOC](#table-of-contents)

##### December

- Two articles on the difficulty on being a software engineer, at that time I didn't really want to choose a software career path. [Patrick McKenzie - Don't Call Yourself A Programmer](http://www.kalzumeus.com/2011/10/28/dont-call-yourself-a-programmer/), [Jeff Atwood - So You Don't Want to be a Programmer After All](http://www.codinghorror.com/blog/2013/04/so-you-dont-want-to-be-a-programmer-after-all.html).
- Some Delphi links for the museum, [Delphi basics](http://www.delphibasics.co.uk/) was the best online resource to find help for Delphi, [using C++ objects in Delphi](http://rvelthuis.de/articles/articles-cppobjs.html), yes I had to use this dinosaur!
- [Armando Fox, David Patterson - Agile Development Using Ruby on Rails](https://www.edx.org/course/agile-development-using-ruby-on-rails-the-basics) where I learned that software wasn't only about Delphi and C++
- Blake Masters notes on Peter Thiel course [Zero to One](https://blakemasters.com/peter-thiels-cs183-startup)

###### October

- [C++ FAQ](https://isocpp.org/faq), [Bjarne Stroustrup](https://www.stroustrup.com) FAQs
- [SpaceSniffer](http://www.uderzo.it/main_products/space_sniffer/)

###### September

- Dealing with legacy code: [I've inherited 200k of spaghetti code](https://programmers.stackexchange.com/questions/155488/ive-inherited-200k-lines-of-spaghetti-code-what-now) from Stack Overflow, Martin Fowler's Refactoring book
- [CSS animations cheatsheet](http://www.justinaguilar.com/animations/), [Git concepts simplified](https://gitolite.com/gcs), [Project Euler](https://projecteuler.net/)

###### June

- On Richard Stallman, [lifestyle](https://framablog.org/2013/06/03/stallman-style-de-vie/), [reasons not to use Google](https://stallman.org/google.html)

##### April

- Learning about UX, [52 week of UX](https://52weeksofux.com/tagged/week_1) and Don Norman's book. Julie Zhuo (Facebook) post [was also a must see](https://medium.com/the-year-of-the-looking-glass/the-future-of-design-in-technology-fe1697e5826).
- [Hack Design](https://hackdesign.org/) is a newsletter for learning web design in 52 weeks, [Balsamiq](https://www.balsamiq.com/) for wireframes, [Dribble](https://dribbble.com/).

------------------------------

#### 2012

[back to TOC](#table-of-contents)

- Andrew Hunt - The Pragmatic Programmer
- Other book recommendations from professionals: [Jeff Atwood](https://blog.codinghorror.com/recommended-reading-for-developers), [George Stocker](https://stackoverflow.com/questions/388242/the-definitive-c-book-guide-and-list), [Scott Hanselman](https://www.hanselman.com/blog/six-essential-language-agnostic-programming-books)
- [Gérard Degoutte - Aide mémoire de mécanique des sols](http://graduateschool.agroparistech.fr/site.php?id=44&fileid=88)
- Mechanics courses : [Laurent Champaney](https://savoir.ensam.eu/moodle/course/view.php?id=1555), [Ecoles des Mines](http://mms2.ensmp.fr/ressources/ens_polycopies.php)
- Two HBR articles annoucing the trend of Big Data that made me change careers [Big Data revolution](https://hbr.org/2012/10/big-data-the-management-revolution), [The sexiest job of the 21st century](https://hbr.org/2012/10/data-scientist-the-sexiest-job-of-the-21st-century), [The Economist - The data deluge](https://www.economist.com/node/15579717)

------------------------------

#### 2011

[back to TOC](#table-of-contents)

- Steve McConnell - Code complete
- Herb Sutter - Exceptional C++
- [Hamish Whittal - Shell scripting](http://www.learnlinux.org.za/courses/build/shell-scripting/shell-scripting.pdf)
- [Eric Pement - Useful one-line scripts for sed](http://sed.sourceforge.net/sed1line.txt)
- Coming from a mechanical engineering background, I also enjoyed _formulaires_-style cheatsheets, [Matthew Miller's for Code Complete](https://www.matthewjmiller.net/files/cc2e_checklists.pdf), [Dave Child on Regular expressions](https://cheatography.com/davechild/cheat-sheets/regular-expressions/), [Design patterns](http://www.webdeveloperjuice.com/demos/cheatsheets/design_pattern_cheatsheet_v1.pdf), [Allen Holub on UML](https://holub.com/uml/). I could also print them in one single piece of paper, which was handy.
- [Microsoft online documentation](https://msdn.microsoft.com/en-us/library/) for learning about Windows subjects such as MFC, DLL, COM, XML etc. [Excel documentation](https://support.microsoft.com/en-us/excel) was also helpful for quick prototyping.
- Travelling with train in Europe : [Railteam search engine](http://www.railteam.fr/).

------------------------------

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
  <a href="https://www.goodreads.com/book/show/22967424-data-science-at-the-command-line"><img src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1411919491l/22967424.jpg" width=100 alt="Janssens"/></a>
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

- Entrepreuneurship: [Andreessen Horowitz](https://a16z.com/), [Rude Baguette](http://www.rudebaguette.com/), [Usine Digitale](https://www.usine-digitale.fr/), [Tech In Asia](http://www.techinasia.com/), [Jason Kottke](http://www.kottke.org/), [Le Monde Informatique](https://www.lemondeinformatique.fr/)
- Research: [Image des mathématiques](http://images.math.cnrs.fr/), [INRIA Interstices](https://interstices.info)
- Civil Engineering: [Yann Le Tilly](https://transid.blogspot.com/)
- Software engineering: [Scott Hanselman](https://www.hanselman.com/blog/), [Uber Engineering](https://eng.uber.com/), [Spotify Engineering](https://engineering.atspotify.com/), [Facebook Engineering](https://code.fb.com/), [GitHub Engineering](https://githubengineering.com/), [Pinterest Engineering](https://medium.com/@Pinterest_Engineering), [Google](https://blog.google), [Etalab](https://www.etalab.gouv.fr), [Datawrapper](https://blog.datawrapper.de), [Erik Bernstein](https://erikbern.com/)
- Data engineering: [Duolingo](http://making.duolingo.com/), [Scalac](https://scalac.io/), [Google Data Analytics](http://cloudblog.withgoogle.com/products/data-analytics), [AWS Big Data](https://aws.amazon.com/fr/blogs/big-data/), [Datadog](https://www.datadoghq.com/blog/), [The Guardian](https://www.theguardian.com/data)
- Web design: [Uninvited Redesign](http://uninvitedredesigns.com/), [Google Web Team](https://developers.google.com/web/updates/)
- General News: [Courrier International](https://www.courrierinternational.com), [Le Monde Videos](https://www.lemonde.fr/videos), [Le Monde Big Browser](http://www.lemonde.fr/big-browser)

#### Social Networks

- Big Data: [Heather Miller](https://www.linkedin.com/in/heather-miller-b7311a5/), [Jacek Laskowski](https://www.linkedin.com/in/jaceklaskowski/), [James Powell](https://www.linkedin.com/in/dontusethiscode/)
- Coding: [Sergei Winitzki](https://www.linkedin.com/in/sergei-winitzki-11a6431/), [Suhan Wijaya](https://www.linkedin.com/in/suhanwijaya/)
- AI: [Jason Mayes](https://www.linkedin.com/in/creativetech/), [Gilles Wainrib](https://www.linkedin.com/in/gilles-wainrib-028a622/), [Lex Fridman](https://www.linkedin.com/in/lexfridman/), [Meghan Zhao](https://www.linkedin.com/in/meghanzhao/)
- Microsoft: [Satya Nadella](https://www.linkedin.com/in/satyanadella/), [Xavier Perret](https://www.linkedin.com/in/xavier-perret/)
- Economics and Leadership: [Bill Aulet](https://www.linkedin.com/in/billaulet/), [Emily Chang](https://www.linkedin.com/in/emilychangbloomberg/), [Jean-Marc Sylvestre](https://www.linkedin.com/in/jean-marc-sylvestre/), [Jean Massiet](https://www.linkedin.com/in/jean-massiet-123a5191/), [Justin Kan](https://www.linkedin.com/in/justinkan/), [Stephen Engle](https://www.linkedin.com/in/stephen-engle-9968ab22/), [Virginie Guyot](https://www.linkedin.com/in/virginieguyot/), [Xinmei Shen](https://www.linkedin.com/in/xinmei-shen-02013b138/)

#### Archive

[back to TOC](#table-of-contents)

- https://hackernoon.com/
- https://threatpost.com
- https://calnewport.com/blog/
- https://alistapart.com/
- https://www.smashingmagazine.com/articles/
- https://www.brainpickings.org/
- https://www.ted.com/talks/
- https://www.theverge.com
- https://www.forbes.com/sites/dailymuse/
- https://lifehacker.com/
- https://blog.simplyhired.com
- https://betterexplained.com

##### Entrepreneurship

- https://www.fastcompany.com
- https://www.paulgraham.com
- https://tim.blog/
- https://techcrunch.com/

##### Research

- https://www.ibm.com/blogs/research/
- http://smai.emath.fr/
- https://www.roadef.org/

##### Civil engineering

- http://civilfrance.typepad.com/blog/
- http://dwf.blogs.com/beyond_the_paper/
- http://ellipsis-autodesk.typepad.com/blog/
- http://perspectives.3ds.com
- http://through-the-interface.typepad.com/through_the_interface/
- http://structurebim.typepad.com/blog/
- http://blog.bouygues-construction.com
- https://blogs.autodesk.com/bim-and-beam/
- https://blogs.solidworks.com/solidworksblog
- https://www.audeladeslignes.com/
- https://www.mobilettre.com/
- http://transid.blogspot.com/
- http://transports.blog.lemonde.fr/

##### Software engineering

- http://www.codinghorror.com/blog/
- http://www.industrie.com/it/
- http://www.nouvellefabrique.fr/blog
- [Algolia Engineering](https://blog.algolia.com/)
- [Yelp Engineering](https://engineeringblog.yelp.com/)
- [Joel Spolsky](https://www.joelonsoftware.com/)
- http://martinfowler.com/
- https://developers.facebook.com/blog/
- https://engineeringblog.yelp.com
- https://michaelfeathers.typepad.com
- https://addyosmani.com/
- [LinkedIn Engineering](https://engineering.linkedin.com/)

##### Programming languages

- http://cpptruths.blogspot.com/
- http://love-python.blogspot.com/
- https://medium.com/javascript-scene
- https://milessabin.com/blog/

##### PropTech

- http://all-about-airbnb.com/
- http://joegebbia.com/blog
- https://zenhabits.net/
- [Airbnb News](https://blog.atairbnb.com/)
- [Airbnb Engineering](https://medium.com/airbnb-engineering)
- [Meilleurs Agents News](https://www.meilleursagents.com/actualite-immobilier/)
- [Meilleurs Agents Engineering](https://medium.com/meilleursagents-engineering)
- [Zillow Porchlight](https://www.zillow.com/blog/)
- [Zillow Research](https://www.zillow.com/research/)
- [Immobilier Danger](https://www.immobilier-danger.com/)

##### Data engineering

- [Maxime Beauchemin](https://medium.com/@maximebeauchemin)
- [Li Haoyi](http://www.lihaoyi.com/)
- [IntelliJ Scala Plugin](https://blog.jetbrains.com/scala/)
- https://towardsdatascience.com/

##### Web design

- https://99u.com
- https://thenextweb.com/
- https://webdesign.tutsplus.com/

##### Newsletters

[back to TOC](#table-of-contents)

- [Database Weekly](https://dbweekly.com/)
- [JavaScript Weekly](https://javascriptweekly.com/)
- [Webops Weekly](https://webopsweekly.com/)
- [Scala Times](https://scalatimes.com)
- [Golang Weekly](https://golangweekly.com/)

### Online courses

[back to TOC](#table-of-contents)

- [Pixar in a box](https://www.khanacademy.org/computing/pixar)
- [Learning how to learn](https://www.coursera.org/learn/learning-how-to-learn)
- [The science of well being](https://www.coursera.org/learn/the-science-of-well-being)

### Repos, toolbox for work-related problems
[back to TOC](#table-of-contents)

#### SORT-ME

New links

<details>

- [`GoogleCloudPlatform/microservices-demo`](https://github.com/GoogleCloudPlatform/microservices-demo)
- [`envoyproxy/envoy`](https://github.com/envoyproxy/envoy)
- [`GoogleCloudPlatform/data-analytics-golden-demo`](https://github.com/GoogleCloudPlatform/data-analytics-golden-demo)
- [`cloudspannerecosystem/harbourbridge`](https://github.com/cloudspannerecosystem/harbourbridge)
- [`powerline/fonts`](https://github.com/powerline/fonts)
- [`ydataai/ydata-profiling`](https://github.com/ydataai/ydata-profiling)
- [`mastodon/mastodon`](https://github.com/mastodon/mastodon)
- [`fredgis/GPS-Data-AI`](https://github.com/fredgis/GPS-Data-AI)
- [`feast-dev/feast`](https://github.com/feast-dev/feast)
- [`deepset-ai/haystack`](https://github.com/deepset-ai/haystack)
- [`pythonprofilers/memory_profiler`](https://github.com/pythonprofilers/memory_profiler)
- [`alexlenail/NN-SVG`](https://github.com/alexlenail/NN-SVG)
- [`brainix/pottery`](https://github.com/brainix/pottery)
- [`tugstugi/dl-colab-notebooks`](https://github.com/tugstugi/dl-colab-notebooks)
- [`docarray/docarray`](https://github.com/docarray/docarray)
- [`holtzy/The-Python-Graph-Gallery`](https://github.com/holtzy/The-Python-Graph-Gallery)
- [`TheAlgorithms/Python`](https://github.com/TheAlgorithms/Python)
- [`mintlify/writer`](https://github.com/mintlify/writer)
- [`glinscott/fishtest`](https://github.com/glinscott/fishtest)
- [`unit8co/darts`](https://github.com/unit8co/darts)
- [`vespa-engine/vespa`](https://github.com/vespa-engine/vespa)
- [`tldraw/tldraw`](https://github.com/tldraw/tldraw)
- [`aws-samples/amazon-sagemaker-integration-with-snowflake`](https://github.com/aws-samples/amazon-sagemaker-integration-with-snowflake)
- [`languagetool-org/languagetool`](https://github.com/languagetool-org/languagetool)
- [`datastaxdevs/bootcamp-fullstack-apps-with-cassandra`](https://github.com/datastaxdevs/bootcamp-fullstack-apps-with-cassandra)
- [`justinfagnani/chessboard-element`](https://github.com/justinfagnani/chessboard-element)
- [`deepchecks/deepchecks`](https://github.com/deepchecks/deepchecks)
- [`node-formidable/formidable`](https://github.com/node-formidable/formidable)
- [`apollos/opencv-practice`](https://github.com/apollos/opencv-practice)
- [`marcusbuffett/command-line-chess`](https://github.com/marcusbuffett/command-line-chess)
- [`aws-samples/aws-cdk-examples`](https://github.com/aws-samples/aws-cdk-examples)
- [`handsonscala/handsonscala`](https://github.com/handsonscala/handsonscala)
- [`tonsky/FiraCode`](https://github.com/tonsky/FiraCode)
- [`google/go-containerregistry`](https://github.com/google/go-containerregistry)
- [`LaurenceRawlings/savify`](https://github.com/LaurenceRawlings/savify)
- [`kdeldycke/awesome-engineering-team-management`](https://github.com/kdeldycke/awesome-engineering-team-management)
- [`rbw/pysnow`](https://github.com/rbw/pysnow)
- [`chimpler/postgres-aws-s3`](https://github.com/chimpler/postgres-aws-s3)
- [`tensorflow/tfjs-models`](https://github.com/tensorflow/tfjs-models)
- [`CSSLab/maia-chess`](https://github.com/CSSLab/maia-chess)
- [`ydavidchen/gcp-mle-outline`](https://github.com/ydavidchen/gcp-mle-outline)
- [`PAIR-code/what-if-tool`](https://github.com/PAIR-code/what-if-tool)
- [`MichalHecko/SSLPoke`](https://github.com/MichalHecko/SSLPoke)
- [`geogebra/geogebra`](https://github.com/geogebra/geogebra)
- [`TeamNewPipe/NewPipe`](https://github.com/TeamNewPipe/NewPipe)
- [`amundsen-io/amundsen`](https://github.com/amundsen-io/amundsen)
- [`datahub-project/datahub`](https://github.com/datahub-project/datahub)
- [`sleuthkit/scalpel`](https://github.com/sleuthkit/scalpel)
- [`numerai/example-scripts`](https://github.com/numerai/example-scripts)

</details>

Old JS links

<details>

- [`CanalTP/navitia`](https://github.com/CanalTP/navitia)
- [`caolan/async`](https://github.com/caolan/async)
- [`cchantep/acolyte`](https://github.com/cchantep/acolyte)
- [`chen-ye/hubot-fb`](https://github.com/chen-ye/hubot-fb)
- [`chrstphrknwtn/grid-clock/`](https://github.com/chrstphrknwtn/grid-clock/)
- [`cjb/GitTorrent`](https://github.com/cjb/GitTorrent)
- [`cloudinary/cloudinary_angular`](https://github.com/cloudinary/cloudinary_angular)
- [`cmpolis/Pagify`](https://github.com/cmpolis/Pagify)
- [`cpbotha/nvpy`](https://github.com/cpbotha/nvpy)
- [`creationix/js-git`](https://github.com/creationix/js-git)
- [`crockpotveggies/tinderbox`](https://github.com/crockpotveggies/tinderbox)
- [`cucumber/cucumber-js`](https://github.com/cucumber/cucumber-js)
- [`cyberglot/awesome-answers`](https://github.com/cyberglot/awesome-answers)
- [`danielgtaylor/aglio`](https://github.com/danielgtaylor/aglio)
- [`databricks/mlflow`](https://github.com/databricks/mlflow)
- [`derikon/awesome-human-motion`](https://github.com/derikon/awesome-human-motion)
- [`derimagia/awesome-alfred-workflows`](https://github.com/derimagia/awesome-alfred-workflows)
- [`DimitarPetrov/stegify`](https://github.com/DimitarPetrov/stegify)
- [`dmajda/pegjs`](https://github.com/dmajda/pegjs)
- [`dominictarr/excel-stream`](https://github.com/dominictarr/excel-stream)
- [`dominictarr/split`](https://github.com/dominictarr/split)
- [`doug-martin/nools`](https://github.com/doug-martin/nools)
- [`dtrebbien/gedit-trim-trailing-whitespace-before-saving-plugin`](https://github.com/dtrebbien/gedit-trim-trailing-whitespace-before-saving-plugin)
- [`elastic/elasticsearch`](https://github.com/elastic/elasticsearch)
- [`eschaefer/PageRank-Checking-Script`](https://github.com/eschaefer/PageRank-Checking-Script)
- [`eush77/object-pairs`](https://github.com/eush77/object-pairs)
- [`facebookincubator/dhcplb`](https://github.com/facebookincubator/dhcplb)
- [`fcambus/nginx-resources`](https://github.com/fcambus/nginx-resources)
- [`firebase/angularfire`](https://github.com/firebase/angularfire)
- [`firebase/examples`](https://github.com/firebase/examples)
- [`firebase/firebase-import`](https://github.com/firebase/firebase-import)
- [`firebase/firebase-simple-login`](https://github.com/firebase/firebase-simple-login)
- [`firebase/firebase-streaming-import`](https://github.com/firebase/firebase-streaming-import)
- [`firebase/firebase-token-generator-node`](https://github.com/firebase/firebase-token-generator-node)
- [`firebase/firechat`](https://github.com/firebase/firechat)
- [`firebase/firesnake`](https://github.com/firebase/firesnake)
- [`firebase/geoFire`](https://github.com/firebase/geoFire)
- [`ftpgrab/ftpgrab`](https://github.com/ftpgrab/ftpgrab)
- [`gabrielpoca/browser-pcm-stream`](https://github.com/gabrielpoca/browser-pcm-stream)
- [`gjtorikian/isBinaryFile`](https://github.com/gjtorikian/isBinaryFile)
- [`GoogleCloudPlatform/functions-framework-nodejs`](https://github.com/GoogleCloudPlatform/functions-framework-nodejs)
- [`graysky2/xscreensaver-aerial/`](https://github.com/graysky2/xscreensaver-aerial/)
- [`gulpjs`](https://github.com/gulpjs)
- [`guptarohit/asciigraph`](https://github.com/guptarohit/asciigraph)
- [`hapijs/joi`](https://github.com/hapijs/joi)
- [`hexojs/hexo`](https://github.com/hexojs/hexo)
- [`humanwhocodes/computer-science-in-javascript`](https://github.com/humanwhocodes/computer-science-in-javascript)
- [`ibaaj/awesome-OpenSourcePhotography`](https://github.com/ibaaj/awesome-OpenSourcePhotography)
- [`igorbarinov/awesome-data-engineering`](https://github.com/igorbarinov/awesome-data-engineering)
- [`InseeFr/Meleze`](https://github.com/InseeFr/Meleze)
- [`jgthms/juketube`](https://github.com/jgthms/juketube)
- [`jonathandion/awesome-emails`](https://github.com/jonathandion/awesome-emails)
- [`jonschlinkert/get-value`](https://github.com/jonschlinkert/get-value)
- [`JorgeBucaran/awesome-fish`](https://github.com/JorgeBucaran/awesome-fish)
- [`josephmisiti/awesome-machine-learning`](https://github.com/josephmisiti/awesome-machine-learning)
- [`jshint/jshint`](https://github.com/jshint/jshint)
- [`JustServerless/awesome-serverless`](https://github.com/JustServerless/awesome-serverless)
- [`jwaterfaucett/awesome-foss-apps`](https://github.com/jwaterfaucett/awesome-foss-apps)
- [`kakoni/awesome-healthcare`](https://github.com/kakoni/awesome-healthcare)
- [`keleshev/schema`](https://github.com/keleshev/schema)
- [`kensho/ng-describe`](https://github.com/kensho/ng-describe)
- [`Kickball/awesome-selfhosted`](https://github.com/Kickball/awesome-selfhosted)
- [`KimberlyMunoz/empathy-in-engineering`](https://github.com/KimberlyMunoz/empathy-in-engineering)
- [`kirbs-/hide_code`](https://github.com/kirbs-/hide_code)
- [`koekeishiya/chunkwm`](https://github.com/koekeishiya/chunkwm)
- [`kovidgoyal/kitty`](https://github.com/kovidgoyal/kitty)
- [`kpdecker/jsdiff`](https://github.com/kpdecker/jsdiff)
- [`krakenjs/lusca`](https://github.com/krakenjs/lusca)
- [`kripken/emscripten`](https://github.com/kripken/emscripten)
- [`kriskowal/q`](https://github.com/kriskowal/q)
- [`leonardomso/33-js-concepts`](https://github.com/leonardomso/33-js-concepts)
- [`ligurio/free-software-testing-books`](https://github.com/ligurio/free-software-testing-books)
- [`lihaoyi/cask`](https://github.com/lihaoyi/cask)
- [`likeastore/ngDialog`](https://github.com/likeastore/ngDialog)
- [`logicalparadox/matcha`](https://github.com/logicalparadox/matcha)
- [`lukeed/sockette`](https://github.com/lukeed/sockette)
- [`madrobby/keymaster`](https://github.com/madrobby/keymaster)
- [`mafintosh/peercast`](https://github.com/mafintosh/peercast)
- [`mafintosh/peerflix`](https://github.com/mafintosh/peerflix)
- [`mapbox/ecs-watchbot`](https://github.com/mapbox/ecs-watchbot)
- [`MariaLetta/free-gophers-pack`](https://github.com/MariaLetta/free-gophers-pack)
- [`mariano-fiorentino/amid`](https://github.com/mariano-fiorentino/amid)
- [`marijnh/tern_for_sublime`](https://github.com/marijnh/tern_for_sublime)
- [`mattinsler/longjohn`](https://github.com/mattinsler/longjohn)
- [`MaximAbramchuck/awesome-interview-questions`](https://github.com/MaximAbramchuck/awesome-interview-questions)
- [`maxogden/cool-ascii-faces`](https://github.com/maxogden/cool-ascii-faces)
- [`mbeaudru/modern-js-cheatsheet`](https://github.com/mbeaudru/modern-js-cheatsheet)
- [`metafloor/bwip-js`](https://github.com/metafloor/bwip-js)
- [`mgechev/angularjs-in-patterns`](https://github.com/mgechev/angularjs-in-patterns)
- [`micromata/awesome-javascript-learning`](https://github.com/micromata/awesome-javascript-learning)
- [`minimaxir/big-list-of-naughty-strings`](https://github.com/minimaxir/big-list-of-naughty-strings)
- [`mmcgrana/services-engineering`](https://github.com/mmcgrana/services-engineering)
- [`montanaflynn/stats`](https://github.com/montanaflynn/stats)
- [`motdotla/node-lambda`](https://github.com/motdotla/node-lambda)
- [`mvdan/sh`](https://github.com/mvdan/sh)
- [`neoziro/push-notify`](https://github.com/neoziro/push-notify)
- [`nicolasdao/google-graphql-functions`](https://github.com/nicolasdao/google-graphql-functions)
- [`noffle/art-of-readme`](https://github.com/noffle/art-of-readme)
- [`nvm-sh/nvm`](https://github.com/nvm-sh/nvm)
- [`oortcloud/meteorite`](https://github.com/oortcloud/meteorite)
- [`oortcloud/unofficial-meteor-faq`](https://github.com/oortcloud/unofficial-meteor-faq)
- [`opencompany/awesome-open-company`](https://github.com/opencompany/awesome-open-company)
- [`opfl/google-speech-full-duplex`](https://github.com/opfl/google-speech-full-duplex)
- [`paldepind/flyd`](https://github.com/paldepind/flyd)
- [`Pent/generator-meteor`](https://github.com/Pent/generator-meteor)
- [`pharzan/promiseRunner`](https://github.com/pharzan/promiseRunner)
- [`pinojs/pino`](https://github.com/pinojs/pino)
- [`postcss/postcss`](https://github.com/postcss/postcss)
- [`prismagraphql/prisma`](https://github.com/prismagraphql/prisma)
- [`prnicolas/ScalaMl`](https://github.com/prnicolas/ScalaMl)
- [`pyeve/cerberus`](https://github.com/pyeve/cerberus)
- [`Q42/TrelloScrum`](https://github.com/Q42/TrelloScrum)
- [`qinwf/awesome-R`](https://github.com/qinwf/awesome-R)
- [`Quixotix/gedit-source-code-browser`](https://github.com/Quixotix/gedit-source-code-browser)
- [`ricardobeat/flatkeys`](https://github.com/ricardobeat/flatkeys)
- [`rmurphey/js-assessment`](https://github.com/rmurphey/js-assessment)
- [`rogerpadilla/angular2-minimalist-starter`](https://github.com/rogerpadilla/angular2-minimalist-starter)
- [`roperzh/jroff`](https://github.com/roperzh/jroff)
- [`rwaldron/idiomatic.js`](https://github.com/rwaldron/idiomatic.js)
- [`rwaldron/johnny-five`](https://github.com/rwaldron/johnny-five)
- [`ryanaghdam/has-key-deep`](https://github.com/ryanaghdam/has-key-deep)
- [`samg/timetrap`](https://github.com/samg/timetrap)
- [`SamRagusa/Checkers-Reinforcement-Learning`](https://github.com/SamRagusa/Checkers-Reinforcement-Learning)
- [`samu/angular-table`](https://github.com/samu/angular-table)
- [`sanity-io/litter`](https://github.com/sanity-io/litter)
- [`schematics/schematics`](https://github.com/schematics/schematics)
- [`schollz/progressbar`](https://github.com/schollz/progressbar)
- [`sdras/awesome-actions`](https://github.com/sdras/awesome-actions)
- [`seanhaufler/banned-bluebook`](https://github.com/seanhaufler/banned-bluebook)
- [`senchalabs/connect`](https://github.com/senchalabs/connect)
- [`sfischer13/awesome-ledger`](https://github.com/sfischer13/awesome-ledger)
- [`sger/ElixirBooks`](https://github.com/sger/ElixirBooks)
- [`shift-js/shift-js`](https://github.com/shift-js/shift-js)
- [`shipitjs/shipit`](https://github.com/shipitjs/shipit)
- [`shk3/edx-downloader`](https://github.com/shk3/edx-downloader)
- [`shobrook/BitVision`](https://github.com/shobrook/BitVision)
- [`showcases/data-visualization`](https://github.com/showcases/data-visualization)
- [`showcases/open-journalism`](https://github.com/showcases/open-journalism)
- [`sindresorhus/awesome-nodejs`](https://github.com/sindresorhus/awesome-nodejs)
- [`sindresorhus/filter-obj`](https://github.com/sindresorhus/filter-obj)
- [`sindresorhus/get-port`](https://github.com/sindresorhus/get-port)
- [`sindresorhus/map-obj`](https://github.com/sindresorhus/map-obj)
- [`sindresorhus/mem`](https://github.com/sindresorhus/mem)
- [`sindresorhus/quick-look-plugins`](https://github.com/sindresorhus/quick-look-plugins)
- [`sindresorhus/strip-json-comments`](https://github.com/sindresorhus/strip-json-comments)
- [`sindresorhus/superb`](https://github.com/sindresorhus/superb)
- [`skale-me/skale-engine`](https://github.com/skale-me/skale-engine)
- [`Slava/tern-meteor`](https://github.com/Slava/tern-meteor)
- [`smallwins/spacetime`](https://github.com/smallwins/spacetime)
- [`spikebrehm/isomorphic-tutorial`](https://github.com/spikebrehm/isomorphic-tutorial)
- [`squaremo/amqp.node`](https://github.com/squaremo/amqp.node)
- [`sryza/spark-timeseries`](https://github.com/sryza/spark-timeseries)
- [`streamproc/MediaStreamRecorder`](https://github.com/streamproc/MediaStreamRecorder)
- [`substance/data`](https://github.com/substance/data)
- [`superscriptjs/superscript`](https://github.com/superscriptjs/superscript)
- [`surveyjs/surveyjs`](https://github.com/surveyjs/surveyjs)
- [`syntaqx/serve`](https://github.com/syntaqx/serve)
- [`thoughtbot/design-sprint`](https://github.com/thoughtbot/design-sprint)
- [`timisbusy/node-amqp-stats`](https://github.com/timisbusy/node-amqp-stats)
- [`tjanczuk/iisnode`](https://github.com/tjanczuk/iisnode)
- [`tobiasbueschel/awesome-pokemon`](https://github.com/tobiasbueschel/awesome-pokemon)
- [`TryGhost/Ghost`](https://github.com/TryGhost/Ghost)
- [`tryolabs/fetch-it`](https://github.com/tryolabs/fetch-it)
- [`twobucks/zapsnap`](https://github.com/twobucks/zapsnap)

</details>

#### Prompt

[back to TOC](#table-of-contents)

- [`acheong08/ChatGPT`](https://github.com/acheong08/ChatGPT)
- [`dair-ai/Prompt-Engineering-Guide`](https://github.com/dair-ai/Prompt-Engineering-Guide)
- [`transitive-bullshit/bing-chat`](https://github.com/transitive-bullshit/bing-chat)
- [`transitive-bullshit/chatgpt-api`](https://github.com/transitive-bullshit/chatgpt-api)

#### CSS

[back to TOC](#table-of-contents)

- [`agarrharr/awesome-static-website-services`](https://github.com/agarrharr/awesome-static-website-services)
- [`edwardtufte/tufte-css`](https://github.com/edwardtufte/tufte-css)
- [`ft-interactive/chart-doctor`](https://github.com/ft-interactive/chart-doctor)
- [`jgthms/bulma`](https://github.com/jgthms/bulma)
- [`Siddharth11/Colorful`](https://github.com/Siddharth11/Colorful)

#### JavaScript

[back to TOC](#table-of-contents)

- [`aerogear/create-graphql`](https://github.com/aerogear/create-graphql)
- [`agenda/agenda`](https://github.com/agenda/agenda)
- [`alexpate/awesome-design-systems`](https://github.com/alexpate/awesome-design-systems)
- [`algolia/places`](https://github.com/algolia/places)
- [`AmirTugi/tea-school`](https://github.com/AmirTugi/tea-school)
- [`ampproject/amphtml`](https://github.com/ampproject/amphtml)
- [`appbaseio/reactivesearch`](https://github.com/appbaseio/reactivesearch)
- [`Baremetrics/calendar`](https://github.com/Baremetrics/calendar)
- [`caiogondim/fast-memoize.js`](https://github.com/caiogondim/fast-memoize.js)
- [`bdickason/node-goodreads`](https://github.com/bdickason/node-goodreads)
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
- [`enquirer/enquirer`](https://github.com/enquirer/enquirer)
- [`ethereum/web3.js`](https://github.com/ethereum/web3.js)
- [`ethereumjs/merkle-patricia-tree`](https://github.com/ethereumjs/merkle-patricia-tree)
- [`expo/expo`](https://github.com/expo/expo)
- [`facebook/create-react-app`](https://github.com/facebook/create-react-app)
- [`firebase/functions-samples`](https://github.com/firebase/functions-samples)
- [`gatsbyjs/gatsby`](https://github.com/gatsbyjs/gatsby)
- [`github/hotkey`](https://github.com/github/hotkey)
- [`gnab/remark`](https://github.com/gnab/remark)
- [`googleapis/nodejs-translate`](https://github.com/googleapis/nodejs-translate)
- [`googleapis/nodejs-video-intelligence`](https://github.com/googleapis/nodejs-video-intelligence)
- [`googleapis/nodejs-vision`](https://github.com/googleapis/nodejs-vision)
- [`GoogleCloudPlatform/nodejs-docs-samples`](https://github.com/GoogleCloudPlatform/nodejs-docs-samples)
- [`gothinkster/realworld`](https://github.com/gothinkster/realworld)
- [`guess-js/guess`](https://github.com/guess-js/guess)
- [`googleworkspace/apps-script-samples`](https://github.com/googleworkspace/apps-script-samples)
- [`h2non/videoshow`](https://github.com/h2non/videoshow)
- [`hasura/graphqurl`](https://github.com/hasura/graphqurl)
- [`hodgef/simple-keyboard`](https://github.com/hodgef/simple-keyboard)
- [`hql287/Manta`](https://github.com/hql287/Manta)
- [`imbrn/v8n`](https://github.com/imbrn/v8n)
- [`indutny/elliptic`](https://github.com/indutny/elliptic)
- [`inorganik/countUp.js`](https://github.com/inorganik/countUp.js)
- [`jakesgordon/javascript-state-machine`](https://github.com/jakesgordon/javascript-state-machine)
- [`josdejong/mathjs`](https://github.com/josdejong/mathjs)
- [`js13kGames/resources`](https://github.com/js13kGames/resources)
- [`juliuste/projections`](https://github.com/juliuste/projections)
- [`juliuste/sncf`](https://github.com/juliuste/sncf)
- [`lokesh/color-thief`](https://github.com/lokesh/color-thief)
- [`lovell/sharp`](https://github.com/lovell/sharp)
- [`karpathy/convnetjs`](https://github.com/karpathy/convnetjs)
- [`khaosdoctor/gotql`](https://github.com/khaosdoctor/gotql)
- [`klaussinani/signale`](https://github.com/klaussinani/signale)
- [`kwhitley/treeize`](https://github.com/kwhitley/treeize)
- [`lerna/lerna`](https://github.com/lerna/lerna)
- [`lhartikk/naivechain`](https://github.com/lhartikk/naivechain)
- [`localForage/localForage`](https://github.com/localForage/localForage)
- [`lukechilds/keyv`](https://github.com/lukechilds/keyv)
- [`KaTeX/KaTeX`](https://github.com/KaTeX/KaTeX)
- [`mozilla/readability`](https://github.com/mozilla/readability)
- [`mafintosh/csv-parser`](https://github.com/mafintosh/csv-parser)
- [`mapbox/pixelmatch`](https://github.com/mapbox/pixelmatch)
- [`mapbox/polylabel`](https://github.com/mapbox/polylabel)
- [`maticzav/emma-cli`](https://github.com/maticzav/emma-cli)
- [`mdn/webextensions-examples`](https://github.com/mdn/webextensions-examples)
- [`mholt/PapaParse`](https://github.com/mholt/PapaParse)
- [`microlinkhq/metascraper`](https://github.com/microlinkhq/metascraper)
- [`microsoft/just`](https://github.com/microsoft/just)
- [`microsoft/napajs`](https://github.com/microsoft/napajs)
- [`mikeal/r2`](https://github.com/mikeal/r2)
- [`mixu/markdown-styles`](https://github.com/mixu/markdown-styles)
- [`mkdocs/mkdocs`](https://github.com/mkdocs/mkdocs)
- [`mljs/savitzky-golay`](https://github.com/mljs/savitzky-golay)
- [`mobxjs/mobx`](https://github.com/mobxjs/mobx)
- [`mourner/flatbush`](https://github.com/mourner/flatbush)
- [`neherlab/covid19_scenarios`](https://github.com/neherlab/covid19_scenarios)
- [`nemtsov/json-mask`](https://github.com/nemtsov/json-mask)
- [`Netflix/falcor`](https://github.com/Netflix/falcor)
- [`Netflix/pollyjs`](https://github.com/Netflix/pollyjs)
- [`nicolas-van/sonant-x-live`](https://github.com/nicolas-van/sonant-x-live)
- [`nhn/tui.calendar`](https://github.com/nhn/tui.calendar)
- [`nuxt/nuxt.js`](https://github.com/nuxt/nuxt.js)
- [`openexchangerates/accounting.js`](https://github.com/openexchangerates/accounting.js)
- [`ostera/tldr.jsx`](https://github.com/ostera/tldr.jsx)
- [`overleaf/overleaf`](https://github.com/overleaf/overleaf)
- [`panrafal/depthy`](https://github.com/panrafal/depthy)
- [`panzerdp/voca`](https://github.com/panzerdp/voca)
- [`paulhoughton/mortgage`](https://github.com/paulhoughton/mortgage)
- [`pd4d10/octohint`](https://github.com/pd4d10/octohint)
- [`peterbraden/node-opencv`](https://github.com/peterbraden/node-opencv)
- [`phoboslab/underrun`](https://github.com/phoboslab/underrun)
- [`picturepan2/spectre`](https://github.com/picturepan2/spectre)
- [`ProseMirror/prosemirror`](https://github.com/ProseMirror/prosemirror)
- [`przemyslawpluta/node-youtube-dl`](https://github.com/przemyslawpluta/node-youtube-dl)
- [`PrismJS/prism`](https://github.com/PrismJS/prism)
- [`rough-stuff/wired-elements`](https://github.com/rough-stuff/wired-elements)
- [`salsita/node-pg-migrate`](https://github.com/salsita/node-pg-migrate)
- [`sindresorhus/awesome-electron`](https://github.com/sindresorhus/awesome-electron)
- [`sindresorhus/cli-spinners`](https://github.com/sindresorhus/cli-spinners)
- [`sindresorhus/fkill-cli`](https://github.com/sindresorhus/fkill-cli)
- [`sindresorhus/on-change`](https://github.com/sindresorhus/on-change)
- [`sindresorhus/pageres`](https://github.com/sindresorhus/pageres)
- [`sindresorhus/Plash`](https://github.com/sindresorhus/Plash)
- [`SamVerschueren/listr`](https://github.com/SamVerschueren/listr)
- [`SBoudrias/Inquirer.js`](https://github.com/SBoudrias/Inquirer.js)
- [`Schmavery/facebook-chat-api`](https://github.com/Schmavery/facebook-chat-api)
- [`serialport/node-serialport`](https://github.com/serialport/node-serialport)
- [`segmentio/nightmare`](https://github.com/segmentio/nightmare)
- [`shelljs/shelljs`](https://github.com/shelljs/shelljs)
- [`spencermountain/spacetime`](https://github.com/spencermountain/spacetime)
- [`sql-js/sql.js`](https://github.com/sql-js/sql.js)
- [`sqreen/awesome-nodejs-projects`](https://github.com/sqreen/awesome-nodejs-projects)
- [`statsd/statsd`](https://github.com/statsd/statsd)
- [`substack/stream-handbook`](https://github.com/substack/stream-handbook)
- [`surveyjs/survey-library`](https://github.com/surveyjs/survey-library)
- [`thedevs-network/kutt`](https://github.com/thedevs-network/kutt)
- [`tj/node-prune`](https://github.com/tj/node-prune)
- [`tombaranowicz/AmazonPricesMonitoring`](https://github.com/tombaranowicz/AmazonPricesMonitoring)
- [`typicode/json-server`](https://github.com/typicode/json-server)
- [`Unitech/pm2`](https://github.com/Unitech/pm2)
- [`trufflesuite/truffle`](https://github.com/trufflesuite/truffle)
- [`validatorjs/validator.js`](https://github.com/validatorjs/validator.js)
- [`vega/vega-lite`](https://github.com/vega/vega-lite)
- [`visgl/loaders.gl`](https://github.com/visgl/loaders.gl)
- [`xtermjs/xterm.js`](https://github.com/xtermjs/xterm.js)
- [`Yomguithereal/mnemonist`](https://github.com/Yomguithereal/mnemonist)
- [`ziishaned/dumper.js`](https://github.com/ziishaned/dumper.js)
- [`zotero/zotero`](https://github.com/zotero/zotero)
- [`williamngan/pts`](https://github.com/williamngan/pts)
- [`AaronCQL/katex-github-chrome-extension`](https://github.com/AaronCQL/katex-github-chrome-extension)

###### Visualization

- [`apache/incubator-echarts`](https://github.com/apache/incubator-echarts)
- [`d3/d3-hierarchy`](https://github.com/d3/d3-hierarchy)
- [`highcharts/highcharts`](https://github.com/highcharts/highcharts)
- [`keplergl/kepler.gl`](https://github.com/keplergl/kepler.gl)
- [`zalando/tech-radar`](https://github.com/zalando/tech-radar)

###### Testing

- [`Automattic/expect.js`](https://github.com/Automattic/expect.js)
- [`Browsersync/browser-sync`](https://github.com/Browsersync/browser-sync)
- [`facebook/jest`](https://github.com/facebook/jest)
- [`getgauge/taiko`](https://github.com/getgauge/taiko)
- [`microsoft/playwright`](https://github.com/microsoft/playwright)
- [`mochajs/mocha`](https://github.com/mochajs/mocha)
- [`puppeteer/puppeteer`](https://github.com/puppeteer/puppeteer)

###### Frontend
- [`angular/angular.js`](https://github.com/angular/angular.js)
- [`ant-design/ant-design`](https://github.com/ant-design/ant-design)
- [`formium/formik`](https://github.com/formium/formik)
- [`space10-community/conversational-form`](https://github.com/space10-community/conversational-form)
- [`stimulusjs/stimulus`](https://github.com/stimulusjs/stimulus)
- [`uNmAnNeR/imaskjs`](https://github.com/uNmAnNeR/imaskjs)
- [`visionmedia/page.js`](https://github.com/visionmedia/page.js)

###### Backend
- [`agershun/alasql`](https://github.com/agershun/alasql)
- [`andris9/Nodemailer`](https://github.com/andris9/Nodemailer)
- [`azat-co/http2-express`](https://github.com/azat-co/http2-express)
- [`mongo-express/mongo-express`](https://github.com/mongo-express/mongo-express)
- [`mrvautin/expressCart`](https://github.com/mrvautin/expressCart)
- [`pnxtech/hydra`](https://github.com/pnxtech/hydra)
- [`prisma-labs/graphql-prisma-typescript`](https://github.com/prisma-labs/graphql-prisma-typescript)
- [`TravelingTechGuy/express4-passport-template`](https://github.com/TravelingTechGuy/express4-passport-template)
- [`vercel/micro`](https://github.com/vercel/micro)

###### Data engineering
- [`alibaba/pipcook`](https://github.com/alibaba/pipcook)
- [`pilwon/node-google-finance`](https://github.com/pilwon/node-google-finance)
- [`proj4js/proj4js`](https://github.com/proj4js/proj4js)
- [`Turfjs/turf`](https://github.com/Turfjs/turf)

###### Safer JS

- [`addyosmani/es6-tools`](https://github.com/addyosmani/es6-tools)
- [`airbnb/javascript`](https://github.com/airbnb/javascript)
- [`bolshchikov/js-must-watch`](https://github.com/bolshchikov/js-must-watch)
- [`elsewhencode/project-guidelines`](https://github.com/elsewhencode/project-guidelines)
- [`facebook/flow`](https://github.com/facebook/flow)
- [`getify/You-Dont-Know-JS`](https://github.com/getify/You-Dont-Know-JS)
- [`goldbergyoni/nodebestpractices`](https://github.com/goldbergyoni/nodebestpractices)
- [`immutable-js/immutable-js`](https://github.com/immutable-js/immutable-js)
- [`microsoft/TypeScript-Node-Starter`](https://github.com/microsoft/TypeScript-Node-Starter)
- [`ryanmcdermott/clean-code-javascript`](https://github.com/ryanmcdermott/clean-code-javascript)
- [`sindresorhus/eslint-plugin-unicorn`](https://github.com/sindresorhus/eslint-plugin-unicorn)
- [`you-dont-need/You-Dont-Need-Momentjs`](https://github.com/you-dont-need/You-Dont-Need-Momentjs)
- [`z-pattern-matching/z`](https://github.com/z-pattern-matching/z)

###### Tensorflow.js

- [`androidfanatic/tfjs-squats-counter-html`](https://github.com/androidfanatic/tfjs-squats-counter-html)
- [`atanasster/hyperparameters`](https://github.com/atanasster/hyperparameters)
- [`bensonruan/Face-Mask`](https://github.com/bensonruan/Face-Mask)
- [`cstefanache/tfjs-model-view`](https://github.com/cstefanache/tfjs-model-view)
- [`GantMan/nsfw_model`](https://github.com/GantMan/nsfw_model)
- [`huggingface/node-question-answering`](https://github.com/huggingface/node-question-answering)
- [`infinitered/nsfwjs`](https://github.com/infinitered/nsfwjs)
- [`justadudewhohacks/face-api.js`](https://github.com/justadudewhohacks/face-api.js)
- [`justadudewhohacks/opencv4nodejs`](https://github.com/justadudewhohacks/opencv4nodejs)
- [`ml5js/ml5-library`](https://github.com/ml5js/ml5-library)
- [`reiinakano/arbitrary-image-stylization-tfjs`](https://github.com/reiinakano/arbitrary-image-stylization-tfjs)
- [`tensorflow/tfjs-examples`](https://github.com/tensorflow/tfjs-examples)
- [`tensorflow/tfjs`](https://github.com/tensorflow/tfjs)
- [`tupleblog/face-classification-js`](https://github.com/tupleblog/face-classification-js)
- [`victordibia/handtrack.js`](https://github.com/victordibia/handtrack.js)
- [`yemount/pose-animator`](https://github.com/yemount/pose-animator)

##### File formats

- [`11ways/json-dry`](https://github.com/11ways/json-dry)
- [`adrai/flowchart.js`](https://github.com/adrai/flowchart.js)
- [`RussCoder/djvujs`](https://github.com/RussCoder/djvujs)

##### Multimedia
- [`0xfe/vexchords`](https://github.com/0xfe/vexchords)
- [`actions-on-google/actions-on-google-nodejs`](https://github.com/actions-on-google/actions-on-google-nodejs)
- [`google/mediapipe`](https://github.com/google/mediapipe)
- [`naptha/tesseract.js`](https://github.com/naptha/tesseract.js)
- [`NaturalNode/natural`](https://github.com/NaturalNode/natural)
- [`nlp-compromise/fr-compromise`](https://github.com/nlp-compromise/fr-compromise)
- [`spencermountain/compromise`](https://github.com/spencermountain/compromise)
- [`wooorm/franc`](https://github.com/wooorm/franc)
- [`wooorm/retext`](https://github.com/wooorm/retext)

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
- [`jaspervz/todo-http4s-doobie`](https://github.com/jaspervz/todo-http4s-doobie)
- [`julianpeeters/sbt-avrohugger`](https://github.com/julianpeeters/sbt-avrohugger)
- [`jvican/sbt-release-early`](https://github.com/jvican/sbt-release-early)
- [`lightbend/config`](https://github.com/lightbend/config)
- [`lightbend/paradox`](https://github.com/lightbend/paradox)
- [`lihaoyi/Ammonite`](https://github.com/lihaoyi/Ammonite)
- [`lihaoyi/requests-scala`](https://github.com/lihaoyi/requests-scala)
- [`lihaoyi/sourcecode`](https://github.com/lihaoyi/sourcecode)
- [`ktoso/sbt-jmh`](https://github.com/ktoso/sbt-jmh)
- [`kailuowang/henkan`](https://github.com/kailuowang/henkan)
- [`lagom/lagom`](https://github.com/lagom/lagom)
- [`linkedin/isolation-forest`](https://github.com/linkedin/isolation-forest)
- [`lucidsoftware/relate`](https://github.com/lucidsoftware/relate)
- [`marcus-nl/scala-impatient-2nd-ed`](https://github.com/marcus-nl/scala-impatient-2nd-ed)
- [`marcuslonnberg/sbt-docker`](https://github.com/marcuslonnberg/sbt-docker)
- [`mdr/ascii-graphs`](https://github.com/mdr/ascii-graphs)
- [`Netflix/atlas`](https://github.com/Netflix/atlas)
- [`novakov-alexey/scala-service.g8`](https://github.com/novakov-alexey/scala-service.g8)
- [`pathikrit/better-files`](https://github.com/pathikrit/better-files)
- [`paulp/sbt-extras`](https://github.com/paulp/sbt-extras)
- [`PiercingDan/spark-Jupyter-AWS`](https://github.com/PiercingDan/spark-Jupyter-AWS)
- [`polynote/polynote`](https://github.com/polynote/polynote)
- [`prisma/graphcool-framework`](https://github.com/prisma/graphcool-framework)
- [`prisma/prisma1`](https://github.com/prisma/prisma1)
- [`pureconfig/pureconfig`](https://github.com/pureconfig/pureconfig)
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
- [`softwaremill/codebrag`](https://github.com/softwaremill/codebrag)
- [`softwaremill/recursion-training`](https://github.com/softwaremill/recursion-training)
- [`softwaremill/sbt-softwaremill`](https://github.com/softwaremill/sbt-softwaremill)
- [`spotify/big-data-rosetta-code`](https://github.com/spotify/big-data-rosetta-code)
- [`spotify/featran`](https://github.com/spotify/featran)
- [`ScorexFoundation/Scorex`](https://github.com/ScorexFoundation/Scorex)
- [`seratch/AWScala`](https://github.com/seratch/AWScala)
- [`shadaj/slinky`](https://github.com/shadaj/slinky)
- [`sksamuel/avro4s`](https://github.com/sksamuel/avro4s)
- [`sksamuel/scrimage`](https://github.com/sksamuel/scrimage)
- [`softwaremill/retry`](https://github.com/softwaremill/retry)
- [`softwaremill/sttp`](https://github.com/softwaremill/sttp)
- [`stripe/bonsai`](https://github.com/stripe/bonsai)
- [`stripe/dagon`](https://github.com/stripe/dagon)
- [`stripe/rainier`](https://github.com/stripe/rainier)
- [`supermanue/example-library`](https://github.com/supermanue/example-library)
- [`superruzafa/visual-scala-reference`](https://github.com/superruzafa/visual-scala-reference)
- [`takezoe/parallelizer`](https://github.com/takezoe/parallelizer)
- [`takezoe/picocli-scala-example`](https://github.com/takezoe/picocli-scala-example)
- [`ThoughtWorksInc/Binding.scala`](https://github.com/ThoughtWorksInc/Binding.scala)
- [`ThoughtWorksInc/DeepLearning.scala`](https://github.com/ThoughtWorksInc/DeepLearning.scala)
- [`triplequote/sbt-scalabench`](https://github.com/triplequote/sbt-scalabench)
- [`tpolecat/doobie`](https://github.com/tpolecat/doobie)
- [`tpolecat/tut`](https://github.com/tpolecat/tut)
- [`typelevel/spire`](https://github.com/typelevel/spire)
- [`typelevel/squants`](https://github.com/typelevel/squants)
- [`twitter/bijection`](https://github.com/twitter/bijection)
- [`twosigma/flint`](https://github.com/twosigma/flint)
- [`underscoreio/shapeless-guide`](https://github.com/underscoreio/shapeless-guide)
- [`vegas-viz/Vegas`](https://github.com/vegas-viz/Vegas)
- [`vkostyukov/scalacaster`](https://github.com/vkostyukov/scalacaster)
- [`transcendent-ai-labs/DynaML`](https://github.com/transcendent-ai-labs/DynaML)
- [`xdotai/diff`](https://github.com/xdotai/diff)
- [`wartremover/wartremover`](https://github.com/wartremover/wartremover)
- [`winitzki/sofp`](https://github.com/winitzki/sofp)
- [`wvlet/airframe`](https://github.com/wvlet/airframe)
- [`scalameta/mdoc`](https://github.com/scalameta/mdoc)

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
- [`databricks-academy/scalable-machine-learning-with-apache-spark-english`](https://github.com/scalable-machine-learning-with-apache-spark-english)
- [`databricks-academy/data-engineering-with-databricks-english`](https://github.com/databricks-academy/data-engineering-with-databricks-english)
- [`databricks-demos/dbdemos`](https://github.com/databricks-demos/dbdemos)
- [`databricks/learning-spark`](https://github.com/databricks/learning-spark)
- [`databricks/spark-sklearn`](https://github.com/databricks/spark-sklearn)
- [`databricks/tensorframes`](https://github.com/databricks/tensorframes)
- [`databrickslabs/dbx`](https://github.com/databrickslabs/dbx)
- [`delta-io/delta`](https://github.com/delta-io/delta)
- [`GoogleCloudDataproc/initialization-actions`](https://github.com/GoogleCloudDataproc/initialization-actions)
- [`hadoopecosystemtable/hadoopecosystemtable.github.io`](https://github.com/hadoopecosystemtable/hadoopecosystemtable.github.io)
- [`holdenk/spark-testing-base`](https://github.com/holdenk/spark-testing-base)
- [`hortonworks-gallery/zeppelin-notebooks`](https://github.com/hortonworks-gallery/zeppelin-notebooks)
- [`KKBOX/spark-deployer`](https://github.com/KKBOX/spark-deployer)
- [`MarkCLewis/BigDataAnalyticswithSpark`](https://github.com/MarkCLewis/BigDataAnalyticswithSpark)
- [`nchammas/flintrock`](https://github.com/nchammas/flintrock)
- [`NVIDIA/spark-xgboost-examples`](https://github.com/NVIDIA/spark-xgboost-examples)
- [`spotify/scio`](https://github.com/spotify/scio)
- [`sryza/aas`](https://github.com/sryza/aas)

#### Python

[Back to TOC](#table-of-contents)

##### Machine Learning

- [`8080labs/pyforest`](https://github.com/8080labs/pyforest)
- [`alexjc/neural-enhance`](https://github.com/alexjc/neural-enhance)
- [`ankush-me/SynthText`](https://github.com/ankush-me/SynthText)
- [`apache/incubator-mxnet`](https://github.com/apache/incubator-mxnet)
- [`argman/EAST`](https://github.com/argman/EAST)
- [`aws/amazon-sagemaker-examples`](https://github.com/aws/amazon-sagemaker-examples)
- [`Azure-Samples/cognitive-services-speech-sdk`](https://github.com/Azure-Samples/cognitive-services-speech-sdk)
- [`CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers`](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers)
- [`biubug6/Face-Detector-1MB-with-landmark`](https://github.com/biubug6/Face-Detector-1MB-with-landmark)
- [`clovaai/CRAFT-pytorch`](https://github.com/clovaai/CRAFT-pytorch)
- [`clovaai/deep-text-recognition-benchmark`](https://github.com/clovaai/deep-text-recognition-benchmark)
- [`dask/dask-tutorial`](https://github.com/dask/dask-tutorial)
- [`dask/dask`](https://github.com/dask/dask)
- [`davidsandberg/facenet`](https://github.com/davidsandberg/facenet)
- [`deepmind/kinetics-i3d`](https://github.com/deepmind/kinetics-i3d)
- [`deezer/spleeter`](https://github.com/deezer/spleeter)
- [`dennybritz/nn-from-scratch`](https://github.com/dennybritz/nn-from-scratch)
- [`dmlc/gluon-cv`](https://github.com/dmlc/gluon-cv)
- [`dmlc/treelite`](https://github.com/dmlc/treelite)
- [`dmlc/xgboost`](https://github.com/dmlc/xgboost)
- [`duolingo/halflife-regression`](https://github.com/duolingo/halflife-regression)
- [`emilwallner/Coloring-greyscale-images`](https://github.com/emilwallner/Coloring-greyscale-images)
- [`explosion/spaCy`](https://github.com/explosion/spaCy)
- [`facebook/prophet`](https://github.com/facebook/prophet)
- [`facebookresearch/semi-supervised-ImageNet1K-models`](https://github.com/facebookresearch/semi-supervised-ImageNet1K-models)
- [`facebookresearch/VideoPose3D`](https://github.com/facebookresearch/VideoPose3D)
- [`fastai/fastai`](https://github.com/fastai/fastai)
- [`fastai/fastpages`](https://github.com/fastai/fastpages)
- [`flairNLP/flair`](https://github.com/flairNLP/flair)
- [`google/making_with_ml`](https://github.com/google/making_with_ml)
- [`googleapis/python-aiplatform`](https://github.com/googleapis/python-aiplatform)
- [`GoogleCloudPlatform/ai-platform-samples`](https://github.com/GoogleCloudPlatform/ai-platform-samples)
- [`GoogleCloudPlatform/data-science-on-gcp`](https://github.com/GoogleCloudPlatform/data-science-on-gcp)
- [`GoogleCloudPlatform/ml-design-patterns`](https://github.com/GoogleCloudPlatform/ml-design-patterns)
- [`GoogleCloudPlatform/mlops-with-vertex-ai`](https://github.com/GoogleCloudPlatform/mlops-with-vertex-ai)
- [`GoogleCloudPlatform/realtime-embeddings-matching`](https://github.com/GoogleCloudPlatform/realtime-embeddings-matching)
- [`hill-a/stable-baselines`](https://github.com/hill-a/stable-baselines)
- [`hundredblocks/ml-powered-applications`](https://github.com/hundredblocks/ml-powered-applications)
- [`idealo/image-super-resolution`](https://github.com/idealo/image-super-resolution)
- [`idealo/imagededup`](https://github.com/idealo/imagededup)
- [`ismir/mir-datasets`](https://github.com/ismir/mir-datasets)
- [`jakevdp/PythonDataScienceHandbook`](https://github.com/jakevdp/PythonDataScienceHandbook)
- [`karpathy/neuraltalk2`](https://github.com/karpathy/neuraltalk2)
- [`krishnaik06/Kaggle-Competitions`](https://github.com/krishnaik06/Kaggle-Competitions)
- [`kubeflow/pipelines`](https://github.com/kubeflow/pipelines)
- [`kvfrans/deepcolor`](https://github.com/kvfrans/deepcolor)
- [`kymatio/kymatio`](https://github.com/kymatio/kymatio)
- [`laurenshareshian/home_price_estimator`](https://github.com/laurenshareshian/home_price_estimator)
- [`MBKraus/Predicting_real_estate_prices_using_scikit-learn`](https://github.com/MBKraus/Predicting_real_estate_prices_using_scikit-learn)
- [`MhLiao/TextBoxes_plusplus`](https://github.com/MhLiao/TextBoxes_plusplus)
- [`microsoft/CNTK`](https://github.com/microsoft/CNTK)
- [`microsoft/DMTK`](https://github.com/microsoft/DMTK)
- [`microsoft/forecasting`](https://github.com/microsoft/forecasting)
- [`microsoft/LightGBM`](https://github.com/microsoft/LightGBM)
- [`microsoft/MLOpsPython`](https://github.com/microsoft/MLOpsPython)
- [`microsoft/recommenders`](https://github.com/microsoft/recommenders)
- [`microsoft/SynapseML`](https://github.com/microsoft/SynapseML)
- [`mittagessen/kraken`](https://github.com/mittagessen/kraken)
- [`nok/sklearn-porter`](https://github.com/nok/sklearn-porter)
- [`optimizely/hyperloglog`](https://github.com/optimizely/hyperloglog)
- [`pytorch/fairseq`](https://github.com/pytorch/fairseq)
- [`pytorch/serve`](https://github.com/pytorch/serve)
- [`random-forests/tutorials`](https://github.com/random-forests/tutorials)
- [`richzhang/colorization`](https://github.com/richzhang/colorization)
- [`rohitrango/automatic-watermark-detection`](https://github.com/rohitrango/automatic-watermark-detection)
- [`Rudrabha/Lip2Wav`](https://github.com/Rudrabha/Lip2Wav)
- [`ryansmcgee/seirsplus`](https://github.com/ryansmcgee/seirsplus)
- [`spotify/annoy`](https://github.com/spotify/annoy)
- [`statsmodels/statsmodels`](https://github.com/statsmodels/statsmodels)
- [`terryum/awesome-deep-learning-papers`](https://github.com/terryum/awesome-deep-learning-papers)
- [`thekevinscott/ml-classifier-ui`](https://github.com/thekevinscott/ml-classifier-ui)
- [`ThilinaRajapakse/simpletransformers`](https://github.com/ThilinaRajapakse/simpletransformers)
- [`tzutalin/labelImg`](https://github.com/tzutalin/labelImg)
- [`zalandoresearch/fashion-mnist`](https://github.com/zalandoresearch/fashion-mnist)
- [`yahoo/open_nsfw`](https://github.com/yahoo/open_nsfw)
- [`wangzheallen/awesome-human-pose-estimation`](https://github.com/wangzheallen/awesome-human-pose-estimation)
- [`vijishmadhavan/ArtLine`](https://github.com/vijishmadhavan/ArtLine)
- [`ray-project/ray`](https://github.com/ray-project/ray)

##### Visualization

- [`bokeh/bokeh`](https://github.com/bokeh/bokeh)
- [`connorferster/handcalcs`](https://github.com/connorferster/handcalcs)

##### Automation

- [`apache/airflow`](https://github.com/apache/airflow)
- [`astronomer/airflow-guides`](https://github.com/astronomer/airflow-guides)
- [`BasPH/data-pipelines-with-apache-airflow`](https://github.com/BasPH/data-pipelines-with-apache-airflow)
- [`celery/celery`](https://github.com/celery/celery)
- [`CoreyMSchafer/code_snippets`](https://github.com/CoreyMSchafer/code_snippets)
- [`dbader/schedule`](https://github.com/dbader/schedule)
- [`flotpython/course`](https://github.com/flotpython/course)
- [`GoogleCloudPlatform/getting-started-python`](https://github.com/GoogleCloudPlatform/getting-started-python)
- [`GoogleCloudPlatform/python-docs-samples`](https://github.com/GoogleCloudPlatform/python-docs-samples)
- [`mherrmann/selenium-python-helium`](https://github.com/mherrmann/selenium-python-helium)
- [`mlflow/mlflow`](https://github.com/mlflow/mlflow)
- [`Netflix/metaflow`](https://github.com/Netflix/metaflow)
- [`norvig/pytudes`](https://github.com/norvig/pytudes)
- [`postmanlabs/httpbin`](https://github.com/postmanlabs/httpbin)
- [`postmanlabs/postman-code-generators`](https://github.com/postmanlabs/postman-code-generators)
- [`PrefectHQ/prefect`](https://github.com/PrefectHQ/prefect)
- [`probot/probot`](https://github.com/probot/probot)
- [`sgratzl/slack_cleaner2`](https://github.com/sgratzl/slack_cleaner2)
- [`STIXProject/python-stix`](https://github.com/STIXProject/python-stix)
- [`wavexx/screenkey`](https://github.com/wavexx/screenkey)
- [`wilfredinni/python-cheatsheet`](https://github.com/wilfredinni/python-cheatsheet)

##### Environment

- [`berdario/pew`](https://github.com/berdario/pew)
- [`pypa/pipenv`](https://github.com/pypa/pipenv)

##### Notebooks

- [`airbnb/knowledge-repo`](https://github.com/airbnb/knowledge-repo)
- [`austin-taylor/code-vault`](https://github.com/austin-taylor/code-vault)
- [`jupyterlab/jupyterlab`](https://github.com/jupyterlab/jupyterlab)
- [`donnemartin/data-science-ipython-notebooks`](https://github.com/donnemartin/data-science-ipython-notebooks)
- [`m2dsupsdlclass/lectures-labs`](https://github.com/m2dsupsdlclass/lectures-labs)
- [`MarcSkovMadsen/awesome-streamlit`](https://github.com/MarcSkovMadsen/awesome-streamlit)
- [`nteract/hydrogen`](https://github.com/nteract/hydrogen)
- [`nteract/nteract`](https://github.com/nteract/nteract)
- [`riddhishb/ipython-notebooks`](https://github.com/riddhishb/ipython-notebooks)
- [`streamlit/streamlit`](https://github.com/streamlit/streamlit)
- [`WillKoehrsen/Bokeh-Python-Visualization`](https://github.com/WillKoehrsen/Bokeh-Python-Visualization)

##### Safer Python

- [`benoitc/gunicorn`](https://github.com/benoitc/gunicorn)
- [`cosmicpython/code`](https://github.com/cosmicpython/code)
- [`ethanfurman/aenum`](https://github.com/ethanfurman/aenum)
- [`facebookresearch/hydra`](https://github.com/facebookresearch/hydra)
- [`google/python-fire`](https://github.com/google/python-fire)
- [`google/yapf`](https://github.com/google/yapf)
- [`jendrikseipp/vulture`](https://github.com/jendrikseipp/vulture)
- [`psf/black`](https://github.com/psf/black)
- [`PyCQA/bandit`](https://github.com/PyCQA/bandit)
- [`python-poetry/poetry`](https://github.com/python-poetry/poetry)

##### Databases

- [`apache/incubator-superset`](https://github.com/apache/incubator-superset)
- [`AustinReese/UsedVehicleSearch`](https://github.com/AustinReese/UsedVehicleSearch)
- [`codelucas/newspaper`](https://github.com/codelucas/newspaper)
- [`fivethirtyeight/data`](https://github.com/fivethirtyeight/data)
- [`great-expectations/great_expectations`](https://github.com/great-expectations/great_expectations)
- [`openfisca/openfisca-france`](https://github.com/openfisca/openfisca-france)
- [`openfisca/openfisca-paris`](https://github.com/openfisca/openfisca-paris)
- [`saulpw/visidata`](https://github.com/saulpw/visidata)
- [`simonw/datasette`](https://github.com/simonw/datasette)
- [`TomAugspurger/effective-pandas`](https://github.com/TomAugspurger/effective-pandas)

##### SQL

- [`sqlfluff/sqlfluff`](https://github.com/sqlfluff/sqlfluff)
- [`sripathikrishnan/jinjasql`](https://github.com/sripathikrishnan/jinjasql)
- [`tobymao/sqlglot`](https://github.com/tobymao/sqlglot)

##### Microservices

- [`addok/addok`](https://github.com/addok/addok)
- [`aws/chalice`](https://github.com/aws/chalice)
- [`cquest/dvf_as_api`](https://github.com/cquest/dvf_as_api)
- [`DaveParr/snakes_and_lambdas`](https://github.com/DaveParr/snakes_and_lambdas)
- [`Delgan/loguru`](https://github.com/Delgan/loguru)
- [`grycap/scar`](https://github.com/grycap/scar)
- [`irmen/Pyrolite`](https://github.com/irmen/Pyrolite)
- [`powdahound/ec2instances.info`](https://github.com/powdahound/ec2instances.info)
- [`pynecone-io/pynecone`](https://github.com/pynecone-io/pynecone)
- [`tadhgfitzgerald/fifa_ranking`](https://github.com/tadhgfitzgerald/fifa_ranking)
- [`taoufik07/responder`](https://github.com/taoufik07/responder)
- [`tiangolo/fastapi`](https://github.com/tiangolo/fastapi)
- [`Yelp/bravado`](https://github.com/Yelp/bravado)

##### Tensorflow

- [`ageron/handson-ml`](https://github.com/ageron/handson-ml)
- [`ahkarami/Deep-Learning-in-Production`](https://github.com/ahkarami/Deep-Learning-in-Production)
- [`albumentations-team/albumentations`](https://github.com/albumentations-team/albumentations)
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
- [`jtoy/awesome-tensorflow`](https://github.com/jtoy/awesome-tensorflow)
- [`lmoroney/dlaicourse`](https://github.com/lmoroney/dlaicourse)
- [`linkedin/detext`](https://github.com/linkedin/detext)
- [`kabbi159/awesome-image-tagging`](https://github.com/kabbi159/awesome-image-tagging)
- [`keras-team/autokeras`](https://github.com/keras-team/autokeras)
- [`Kulbear/deep-learning-coursera`](https://github.com/Kulbear/deep-learning-coursera)
- [`martin-gorner/tensorflow-mnist-tutorial`](https://github.com/martin-gorner/tensorflow-mnist-tutorial)
- [`martin-gorner/tensorflow-rnn-shakespeare`](https://github.com/martin-gorner/tensorflow-rnn-shakespeare)
- [`mbadry1/DeepLearning.ai-Summary`](https://github.com/mbadry1/DeepLearning.ai-Summary)
- [`nileshkulkarni/csm`](https://github.com/nileshkulkarni/csm)
- [`NVIDIA/vid2vid`](https://github.com/NVIDIA/vid2vid)
- [`sayakpaul/Data-Pipelines-with-TensorFlow-Data-Services-Exercises`](https://github.com/sayakpaul/Data-Pipelines-with-TensorFlow-Data-Services-Exercises)
- [`sebastianruder/NLP-progress`](https://github.com/sebastianruder/NLP-progress)
- [`tensorflow/adanet`](https://github.com/tensorflow/adanet)
- [`tensorflow/docs`](https://github.com/tensorflow/docs)
- [`tensorflow/federated`](https://github.com/tensorflow/federated)
- [`tensorflow/graphics`](https://github.com/tensorflow/graphics)
- [`tensorflow/models`](https://github.com/tensorflow/models)
- [`tensorflow/playground`](https://github.com/tensorflow/playground)
- [`tensorflow/privacy`](https://github.com/tensorflow/privacy)
- [`tensorflow/serving`](https://github.com/tensorflow/serving)
- [`tensorflow/tensorflow`](https://github.com/tensorflow/tensorflow)
- [`tensorflow/tfx`](https://github.com/tensorflow/tfx)

#### Go and native languages

[back to TOC](#table-of-contents)

- [`360EntSecGroup-Skylar/excelize`](https://github.com/360EntSecGroup-Skylar/excelize)
- [`ActiveState/gococo`](https://github.com/ActiveState/gococo)
- [`alda-lang/alda`](https://github.com/alda-lang/alda)
- [`argoproj/argo`](https://github.com/argoproj/argo)
- [`arschles/go-in-5-minutes`](https://github.com/arschles/go-in-5-minutes)
- [`astaxie/beego`](https://github.com/astaxie/beego)
- [`atom-archive/xray`](https://github.com/atom-archive/xray)
- [`austingebauer/go-leetcode`](https://github.com/austingebauer/go-leetcode)
- [`avelino/awesome-go`](https://github.com/avelino/awesome-go)
- [`aws/aws-sdk-go`](https://github.com/aws/aws-sdk-go)
- [`bitly/go-simplejson`](https://github.com/bitly/go-simplejson)
- [`bjorng/wings`](https://github.com/bjorng/wings)
- [`chrislusf/gleam`](https://github.com/chrislusf/gleam)
- [`circleci/go-ecs-ecr`](https://github.com/circleci/go-ecs-ecr)
- [`cstate/cstate`](https://github.com/cstate/cstate)
- [`ethereum/go-ethereum`](https://github.com/ethereum/go-ethereum)
- [`go-jira/jira`](https://github.com/go-jira/jira)
- [`go-redis/redis`](https://github.com/go-redis/redis)
- [`go-resty/resty`](https://github.com/go-resty/resty)
- [`gobuffalo/buffalo`](https://github.com/gobuffalo/buffalo)
- [`gobuffalo/pop`](https://github.com/gobuffalo/pop)
- [`gohugoio/hugo`](https://github.com/gohugoio/hugo)
- [`golang/go`](https://github.com/golang/go)
- [`googleforgames/open-match`](https://github.com/googleforgames/open-match)
- [`hybridgroup/gocv`](https://github.com/hybridgroup/gocv)
- [`harlow/kinesis-consumer`](https://github.com/harlow/kinesis-consumer)
- [`jf-tech/omniparser`](https://github.com/jf-tech/omniparser)
- [`jondot/goweight`](https://github.com/jondot/goweight)
- [`kasvith/kache`](https://github.com/kasvith/kache)
- [`keycastr/keycastr`](https://github.com/keycastr/keycastr)
- [`labstack/echo`](https://github.com/labstack/echo)
- [`MontFerret/ferret`](https://github.com/MontFerret/ferret)
- [`nsqio/nsq`](https://github.com/nsqio/nsq)
- [`oneapi-src/oneDNN`](https://github.com/oneapi-src/oneDNN)
- [`photoprism/photoprism`](https://github.com/photoprism/photoprism)
- [`Shopify/sarama`](https://github.com/Shopify/sarama)
- [`stretchr/testify`](https://github.com/stretchr/testify)
- [`tmaiaroto/aegis`](https://github.com/tmaiaroto/aegis)
- [`TylerBrock/saw`](https://github.com/TylerBrock/saw)
- [`valyala/fasthttp`](https://github.com/valyala/fasthttp)
- [`zenazn/goji`](https://github.com/zenazn/goji)
- [`Y2Z/monolith`](https://github.com/Y2Z/monolith)

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
- [`keycloak/keycloak`](https://github.com/keycloak/keycloak)
- [`lmonkiewicz/spring-rest-validation`](https://github.com/lmonkiewicz/spring-rest-validation)
- [`neo4j-contrib/neo4j-graph-algorithms`](https://github.com/neo4j-contrib/neo4j-graph-algorithms)
- [`oracle/graal`](https://github.com/oracle/graal)
- [`plantuml/plantuml`](https://github.com/plantuml/plantuml)
- [`RichardWarburton/java-8-lambdas-exercises`](https://github.com/RichardWarburton/java-8-lambdas-exercises)
- [`spotify/apollo`](https://github.com/spotify/apollo)
- [`spotify/zoltar`](https://github.com/spotify/zoltar)
- [`splicemachine/spliceengine`](https://github.com/splicemachine/spliceengine)
- [`spring-projects/spring-boot`](https://github.com/spring-projects/spring-boot)
- [`swagger-api/swagger-codegen`](https://github.com/swagger-api/swagger-codegen)
- [`tedyoung/awesome-java8`](https://github.com/tedyoung/awesome-java8)
- [`takari/maven-wrapper`](https://github.com/takari/maven-wrapper)

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
- [`LappleApple/awesome-leading-and-managing`](https://github.com/LappleApple/awesome-leading-and-managing)
- [`papers-we-love/papers-we-love`](https://github.com/papers-we-love/papers-we-love)
- [`robbie-cao/awesome-slides`](https://github.com/robbie-cao/awesome-slides)
- [`rossant/awesome-math`](https://github.com/rossant/awesome-math)
- [`SocialGouv/code-du-travail-numerique`](https://github.com/SocialGouv/code-du-travail-numerique)
- [`rstudio/tufte`](https://github.com/rstudio/tufte)

#### Museum

[back to TOC](#table-of-contents)

- [`a-nikolaev/curseofwar`](https://github.com/a-nikolaev/curseofwar)
- [`alegrand/SMPE`](https://github.com/alegrand/SMPE)
- [`AnthonyCalandra/modern-cpp-features`](https://github.com/AnthonyCalandra/modern-cpp-features)
- [`astralapp/astral`](https://github.com/astralapp/astral)
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
- [`JuliaLang/julia`](https://github.com/JuliaLang/julia)
- [`libvips/libvips`](https://github.com/libvips/libvips)
- [`LeCoupa/awesome-cheatsheets`](https://github.com/LeCoupa/awesome-cheatsheets)
- [`libretro/RetroArch`](https://github.com/libretro/RetroArch)
- [`microsoft/MS-DOS`](https://github.com/microsoft/MS-DOS)
- [`microsoft/mssql-scripter`](https://github.com/microsoft/mssql-scripter)
- [`microsoft/QuantumKatas`](https://github.com/microsoft/QuantumKatas)
- [`magenta/magenta-studio`](https://github.com/magenta/magenta-studio)
- [`matze/mtheme`](https://github.com/matze/mtheme)
- [`neutraltone/awesome-stock-resources`](https://github.com/neutraltone/awesome-stock-resources)
- [`official-stockfish/Stockfish`](https://github.com/official-stockfish/Stockfish)
- [`sharetribe/sharetribe`](https://github.com/sharetribe/sharetribe)
- [`simdjson/simdjson`](https://github.com/simdjson/simdjson)
- [`sporto/awesome-elm`](https://github.com/sporto/awesome-elm)
- [`stan-dev/math`](https://github.com/stan-dev/math)
- [`tum-vision/fastms`](https://github.com/tum-vision/fastms)
- [`Unity-Technologies/unitysimulation-coronavirus-example`](https://github.com/Unity-Technologies/unitysimulation-coronavirus-example)
- [`VBA-tools/VBA-Web`](https://github.com/VBA-tools/VBA-Web)
- [`xbpeng/DeepMimic`](https://github.com/xbpeng/DeepMimic)

#### DevOps

[back to TOC](#table-of-contents)

- [`awesome-selfhosted/awesome-selfhosted`](https://github.com/awesome-selfhosted/awesome-selfhosted)
- [`aws/aws-sam-cli`](https://github.com/aws/aws-sam-cli)
- [`awsdocs/aws-doc-sdk-examples`](https://github.com/awsdocs/aws-doc-sdk-examples)
- [`awslabs/ec2-spot-labs`](https://github.com/awslabs/ec2-spot-labs)
- [`awslabs/ecs-nginx-reverse-proxy`](https://github.com/awslabs/ecs-nginx-reverse-proxy)
- [`aws-samples/amazon-ecs-java-microservices`](https://github.com/aws-samples/amazon-ecs-java-microservices)
- [`balena-io/etcher`](https://github.com/balena-io/etcher)
- [`brotandgames/ciao`](https://github.com/brotandgames/ciao)
- [`devspace/awesome-github-templates`](https://github.com/devspace/awesome-github-templates)
- [`donnemartin/awesome-aws`](https://github.com/donnemartin/awesome-aws)
- [`imgproxy/imgproxy`](https://github.com/imgproxy/imgproxy)
- [`mattermost/mattermost-server`](https://github.com/mattermost/mattermost-server)
- [`nektos/act`](https://github.com/nektos/act)
- [`nextcloud/nextcloudpi`](https://github.com/nextcloud/nextcloudpi)
- [`nicolargo/glances`](https://github.com/nicolargo/glances)
- [`OptimalBits/redbird`](https://github.com/OptimalBits/redbird)
- [`osquery/osquery`](https://github.com/osquery/osquery)
- [`pcottle/learnGitBranching`](https://github.com/pcottle/learnGitBranching)
- [`petervanderdoes/gitflow-avh`](https://github.com/petervanderdoes/gitflow-avh)
- [`rgburke/grv`](https://github.com/rgburke/grv)
- [`spotify/styx`](https://github.com/spotify/styx)
- [`SimulatedGREG/nginx-cheatsheet`](https://github.com/SimulatedGREG/nginx-cheatsheet)
- [`snapcore/snapcraft`](https://github.com/snapcore/snapcraft)
- [`spinnaker/spinnaker`](https://github.com/spinnaker/spinnaker)
- [`trimstray/test-your-sysadmin-skills`](https://github.com/trimstray/test-your-sysadmin-skills)
- [`wallabag/wallabag`](https://github.com/wallabag/wallabag)
- [`swanson/stringer`](https://github.com/swanson/stringer)

##### Monitoring

- [`allinurl/goaccess`](https://github.com/allinurl/goaccess)
- [`healthchecks/healthchecks`](https://github.com/healthchecks/healthchecks)
- [`monitoringartist/grafana-aws-cloudwatch-dashboards`](https://github.com/monitoringartist/grafana-aws-cloudwatch-dashboards)
- [`jorgebastida/awslogs`](https://github.com/jorgebastida/awslogs)

##### Continuous Integration

- [`actions/example-services`](https://github.com/actions/example-services)
- [`actions/starter-workflows`](https://github.com/actions/starter-workflows)
- [`awsdocs/aws-cloudformation-user-guide`](https://github.com/awsdocs/aws-cloudformation-user-guide)
- [`awslabs/aws-cloudformation-templates`](https://github.com/awslabs/aws-cloudformation-templates)
- [`aws-samples/ecs-refarch-cloudformation`](https://github.com/aws-samples/ecs-refarch-cloudformation)
- [`cloudtools/troposphere`](https://github.com/cloudtools/troposphere)
- [`MonsantoCo/cloudformation-template-generator`](https://github.com/MonsantoCo/cloudformation-template-generator)
- [`nathanpeck/awesome-ecs`](https://github.com/nathanpeck/awesome-ecs)
- [`runatlantis/atlantis`](https://github.com/runatlantis/atlantis)
- [`sindresorhus/refined-github`](https://github.com/sindresorhus/refined-github)
- [`stefanbuck/awesome-browser-extensions-for-github`](https://github.com/stefanbuck/awesome-browser-extensions-for-github)

###### Docker and Kubernetes

- [`cablespaghetti/kubeadm-aws`](https://github.com/cablespaghetti/kubeadm-aws)
- [`docker-slim/docker-slim`](https://github.com/docker-slim/docker-slim)
- [`dokku/dokku`](https://github.com/dokku/dokku)
- [`kelseyhightower/kubernetes-the-hard-way`](https://github.com/kelseyhightower/kubernetes-the-hard-way)
- [`spotty-cloud/spotty`](https://github.com/spotty-cloud/spotty)
- [`wagoodman/dive`](https://github.com/wagoodman/dive)

###### Site Reliability

- [`binhnguyennus/awesome-scalability`](https://github.com/binhnguyennus/awesome-scalability)

###### Functions

- [`asrivas/work-less-do-more`](https://github.com/asrivas/work-less-do-more)
- [`aws-samples/lambda-refarch-image-moderation-chatbot`](https://github.com/aws-samples/lambda-refarch-image-moderation-chatbot)
- [`GoogleCloudPlatform/functions-framework-ruby`](https://github.com/GoogleCloudPlatform/functions-framework-ruby)
- [`openfaas/faas`](https://github.com/openfaas/faas)
- [`serverless/examples`](https://github.com/serverless/examples)
- [`serverless/plugins`](https://github.com/serverless/plugins)
- [`serverless/serverless-graphql-blog`](https://github.com/serverless/serverless-graphql-blog)
- [`serverless/serverless`](https://github.com/serverless/serverless)
- [`minio/minio`](https://github.com/minio/minio)

##### MLOps

- [`aws-samples/lambda-refarch-imagerecognition`](https://github.com/aws-samples/lambda-refarch-imagerecognition)
- [`axa-group/Parsr`](https://github.com/axa-group/Parsr)
- [`full-stack-deep-learning/course-gitbook`](https://github.com/full-stack-deep-learning/course-gitbook)
- [`GoogleCloudPlatform/mlops-on-gcp/`](https://github.com/GoogleCloudPlatform/mlops-on-gcp/tree/master/workshops/)
- [`mercari/ml-system-design-pattern`](https://github.com/mercari/ml-system-design-pattern)
- [`GoogleCloudPlatform/mlops-on-gcp`](https://github.com/GoogleCloudPlatform/mlops-on-gcp)
- [`GoogleCloudPlatform/training-data-analyst`](https://github.com/GoogleCloudPlatform/training-data-analyst)
- [`kubeflow/kubeflow`](https://github.com/kubeflow/kubeflow)
- [`ml874/Data-Engineering-on-GCP-Cheatsheet`](https://github.com/ml874/Data-Engineering-on-GCP-Cheatsheet)
- [`machine-learning-apps/actions-ml-cicd`](https://github.com/machine-learning-apps/actions-ml-cicd)
- [`machine-learning-projects/machine-learning-recipes`](https://github.com/machine-learning-projects/machine-learning-recipes)
- [`uber/ludwig`](https://github.com/uber/ludwig)

#### Databases

[back to TOC](#table-of-contents)

- [`calogica/dbt-expectations`](https://github.com/calogica/dbt-expectations)
- [`citusdata/postgresql-hll`](https://github.com/citusdata/postgresql-hll)
- [`citusdata/postgresql-topn`](https://github.com/citusdata/postgresql-topn)
- [`duckdb/duckdb`](https://github.com/duckdb/duckdb)
- [`dgraph-io/dgraph`](https://github.com/dgraph-io/dgraph)
- [`dbt-labs/dbt-audit-helper`](https://github.com/dbt-labs/dbt-audit-helper)
- [`dbt-labs/dbt-external-tables`](https://github.com/dbt-labs/dbt-external-tables)
- [`ept/ddia-references`](https://github.com/ept/ddia-references)
- [`fastogt/fastonosql`](https://github.com/fastogt/fastonosql)
- [`fishtown-analytics/dbt`](https://github.com/fishtown-analytics/dbt)
- [`getredash/redash`](https://github.com/getredash/redash)
- [`GoogleCloudPlatform/bigquery-oreilly-book`](https://github.com/GoogleCloudPlatform/bigquery-oreilly-book)
- [`GoogleCloudPlatform/bigquery-utils`](https://github.com/GoogleCloudPlatform/bigquery-utils)
- [`heathermiller/dist-prog-book`](https://github.com/heathermiller/dist-prog-book)
- [`Hiflylabs/awesome-dbt`](https://github.com/Hiflylabs/awesome-dbt)
- [`HTTPArchive/bigquery`](https://github.com/HTTPArchive/bigquery)
- [`HTTPArchive/httparchive.org`](https://github.com/HTTPArchive/httparchive.org)
- [`influxdata/influxdb`](https://github.com/influxdata/influxdb)
- [`jwills/dbt-duckdb`](https://github.com/jwills/dbt-duckdb)
- [`LINCnil/pia-back`](https://github.com/LINCnil/pia-back)
- [`lesovsky/pgcenter`](https://github.com/lesovsky/pgcenter)
- [`metabase/metabase`](https://github.com/metabase/metabase)
- [`mindsdb/mindsdb`](https://github.com/mindsdb/mindsdb)
- [`PostgREST/postgrest`](https://github.com/PostgREST/postgrest)
- [`prestodb/presto`](https://github.com/prestodb/presto)
- [`rethinkdb/rethinkdb`](https://github.com/rethinkdb/rethinkdb)
- [`roaldnefs/awesome-prometheus`](https://github.com/roaldnefs/awesome-prometheus)
- [`snowplow/iglu-central`](https://github.com/snowplow/iglu-central)
- [`sqlpad/sqlpad`](https://github.com/sqlpad/sqlpad)
- [`usefathom/fathom`](https://github.com/usefathom/fathom)
- [`timescale/timescaledb`](https://github.com/timescale/timescaledb)
- [`facebook/rocksdb`](https://github.com/facebook/rocksdb)
- [`GoogleCloudPlatform/bigquery-geo-viz`](https://github.com/GoogleCloudPlatform/bigquery-geo-viz)

#### CLI

[back to TOC](#table-of-contents)

- [`agarrharr/awesome-cli-apps`](https://github.com/agarrharr/awesome-cli-apps)
- [`alebcay/awesome-shell`](https://github.com/alebcay/awesome-shell)
- [`herrbischoff/awesome-command-line-apps`](https://github.com/herrbischoff/awesome-command-line-apps)
- [`jeroenjanssens/data-science-at-the-command-line`](https://github.com/jeroenjanssens/data-science-at-the-command-line)
- [`alexellis/mine-with-docker`](https://github.com/alexellis/mine-with-docker)
- [`clibs/entr`](https://github.com/clibs/entr)
- [`clvv/fasd`](https://github.com/clvv/fasd)
- [`dflemstr/rq`](https://github.com/dflemstr/rq)
- [`google/zx`](https://github.com/google/zx)
- [`HazyResearch/pdftotree`](https://github.com/HazyResearch/pdftotree)
- [`jeffbski/wait-on`](https://github.com/jeffbski/wait-on)
- [`jiahaog/nativefier`](https://github.com/jiahaog/nativefier)
- [`klaussinani/taskbook`](https://github.com/klaussinani/taskbook)
- [`ledger/ledger`](https://github.com/ledger/ledger)
- [`mholt/archiver`](https://github.com/mholt/archiver)
- [`mptre/yank`](https://github.com/mptre/yank)
- [`pstadler/ticker.sh`](https://github.com/pstadler/ticker.sh)
- [`sapegin/shipit`](https://github.com/sapegin/shipit)
- [`wtfutil/wtf`](https://github.com/wtfutil/wtf)
- [`wting/autojump`](https://github.com/wting/autojump)
- [`yudai/gotty`](https://github.com/yudai/gotty)

##### Markdown

- [`jamesramsay/hercule`](https://github.com/jamesramsay/hercule)
- [`mermaid-js/mermaid`](https://github.com/mermaid-js/mermaid)
- [`rust-lang/mdBook`](https://github.com/rust-lang/mdBook)

##### Data Browser

- [`andmarti1424/sc-im`](https://github.com/andmarti1424/sc-im)
- [`dbcli/mssql-cli`](https://github.com/dbcli/mssql-cli)
- [`dbcli/pgcli`](https://github.com/dbcli/pgcli)
- [`jarun/ddgr`](https://github.com/jarun/ddgr)
- [`jarun/googler`](https://github.com/jarun/googler)
- [`pimutils/khal`](https://github.com/pimutils/khal)
- [`santinic/how2`](https://github.com/santinic/how2)
- [`tats/w3m`](https://github.com/tats/w3m)
- [`tstack/lnav`](https://github.com/tstack/lnav)

##### Scripting

- [`akavel/up`](https://github.com/akavel/up)
- [`awslabs/aws-shell`](https://github.com/awslabs/aws-shell)
- [`cmatsuoka/figlet`](https://github.com/cmatsuoka/figlet)
- [`holman/spark`](https://github.com/holman/spark)
- [`idank/explainshell`](https://github.com/idank/explainshell)
- [`koalaman/shellcheck`](https://github.com/koalaman/shellcheck)
- [`nk412/optparse`](https://github.com/nk412/optparse)
- [`oclif/oclif`](https://github.com/oclif/oclif)
- [`ohmyzsh/ohmyzsh`](https://github.com/ohmyzsh/ohmyzsh)
- [`sharkdp/fd`](https://github.com/sharkdp/fd)
- [`sstephenson/bats`](https://github.com/sstephenson/bats)
- [`tldr-pages/tldr`](https://github.com/tldr-pages/tldr)
- [`wallix/awless`](https://github.com/wallix/awless)

##### Code management

- [`AlDanial/cloc`](https://github.com/AlDanial/cloc)
- [`arslanbilal/git-cheat-sheet`](https://github.com/arslanbilal/git-cheat-sheet)
- [`cli/cli`](https://github.com/cli/cli)
- [`ggreer/the_silver_searcher`](https://github.com/ggreer/the_silver_searcher)
- [`git-tips/tips`](https://github.com/git-tips/tips)
- [`github/semantic`](https://github.com/github/semantic)
- [`iterative/dvc`](https://github.com/iterative/dvc)
- [`kamranahmedse/git-standup`](https://github.com/kamranahmedse/git-standup)
- [`lesnitsky/git-tutor`](https://github.com/lesnitsky/git-tutor)
- [`pomber/git-history`](https://github.com/pomber/git-history)
- [`stevemao/awesome-git-addons`](https://github.com/stevemao/awesome-git-addons)

##### Vim

- [`bzg/org-mode`](https://github.com/bzg/org-mode)
- [`metakirby5/codi.vim`](https://github.com/metakirby5/codi.vim)
- [`mhinz/vim-galore`](https://github.com/mhinz/vim-galore)
- [`neovim/neovim`](https://github.com/neovim/neovim)
- [`philc/vimium`](https://github.com/philc/vimium)
- [`vim-syntastic/syntastic`](https://github.com/vim-syntastic/syntastic)

##### Scrapping

- [`alex000kim/nsfw_data_scraper`](https://github.com/alex000kim/nsfw_data_scraper)
- [`aria2/aria2`](https://github.com/aria2/aria2)
- [`coursera-dl/edx-dl`](https://github.com/coursera-dl/edx-dl)
- [`exiftool/exiftool`](https://github.com/exiftool/exiftool)
- [`Ebazhanov/linkedin-skill-assessments-quizzes`](https://github.com/Ebazhanov/linkedin-skill-assessments-quizzes)
- [`iv-org/invidious`](https://github.com/iv-org/invidious)
- [`numfocus/YouTubeVideoTimestamps`](https://github.com/numfocus/YouTubeVideoTimestamps)
- [`rosen-score/lichess-youtube-timestamper`](https://github.com/rosen-score/lichess-youtube-timestamper)
- [`SwapnilSoni1999/spotify-dl`](https://github.com/SwapnilSoni1999/spotify-dl)
- [`tomquirk/linkedin-api`](https://github.com/tomquirk/linkedin-api)
- [`transitive-bullshit/awesome-ffmpeg`](https://github.com/transitive-bullshit/awesome-ffmpeg)
- [`watsonbox/exportify`](https://github.com/watsonbox/exportify)
- [`yt-dlp/yt-dlp`](https://github.com/yt-dlp/yt-dlp)
- [`ytdl-org/youtube-dl`](https://github.com/ytdl-org/youtube-dl)

##### Structured text

- [`benibela/xidel`](https://github.com/benibela/xidel)
- [`BurntSushi/ripgrep`](https://github.com/BurntSushi/ripgrep)
- [`BurntSushi/xsv`](https://github.com/BurntSushi/xsv)
- [`dbohdan/structured-text-tools`](https://github.com/dbohdan/structured-text-tools)
- [`ericchiang/pup`](https://github.com/ericchiang/pup)
- [`jasperes/bash-yaml`](https://github.com/jasperes/bash-yaml)
- [`jehiah/json2csv`](https://github.com/jehiah/json2csv)
- [`mikefarah/yq`](https://github.com/mikefarah/yq)
- [`mithrandie/csvq`](https://github.com/mithrandie/csvq)
- [`sharkdp/bat`](https://github.com/sharkdp/bat)
- [`simeji/jid`](https://github.com/simeji/jid)
- [`stedolan/jq`](https://github.com/stedolan/jq)
- [`tomnomnom/gron`](https://github.com/tomnomnom/gron)

##### Load testing

- [`tsenart/vegeta`](https://github.com/tsenart/vegeta)
- [`wg/wrk`](https://github.com/wg/wrk)

##### Filesystem

- [`ranger/ranger`](https://github.com/ranger/ranger)
- [`rofl0r/ncdu`](https://github.com/rofl0r/ncdu)
- [`EverythingMe/ncdu-s3`](https://github.com/EverythingMe/ncdu-s3)
- [`GoogleCloudPlatform/gcsfuse`](https://github.com/GoogleCloudPlatform/gcsfuse)
- [`libfuse/sshfs`](https://github.com/libfuse/sshfs)

#### Security

[back to TOC](#table-of-contents)

- [`apsdehal/awesome-ctf`](https://github.com/apsdehal/awesome-ctf)
- [`awslabs/git-secrets`](https://github.com/awslabs/git-secrets)
- [`clario-tech/s3-inspector`](https://github.com/clario-tech/s3-inspector)
- [`brannondorsey/wifi-cracking`](https://github.com/brannondorsey/wifi-cracking)
- [`FishermansEnemy/bucket_finder`](https://github.com/FishermansEnemy/bucket_finder)
- [`hak5/bashbunny-payloads`](https://github.com/hak5/bashbunny-payloads)
- [`kfei/slack-cleaner`](https://github.com/kfei/slack-cleaner)
- [`lastpass/lastpass-cli`](https://github.com/lastpass/lastpass-cli)
- [`maxchehab/CSS-Keylogging`](https://github.com/maxchehab/CSS-Keylogging)
- [`meitar/awesome-lockpicking`](https://github.com/meitar/awesome-lockpicking)
- [`openbullet/OpenBullet2`](https://github.com/openbullet/OpenBullet2)
- [`OpenCTI-Platform/opencti`](https://github.com/OpenCTI-Platform/opencti)
- [`projectdiscovery/naabu`](https://github.com/projectdiscovery/naabu)
- [`sa7mon/S3Scanner`](https://github.com/sa7mon/S3Scanner)
- [`traviscross/mtr`](https://github.com/traviscross/mtr)
- [`zricethezav/gitleaks`](https://github.com/zricethezav/gitleaks)

### Quotes

[back to TOC](#table-of-contents)

> "_Thus, I thought dynamic programming was a good name. It was something not even a Congressman could object to. So I used it as an umbrella for my activities_" Richard Bellman

> "_A mathematician is a device for turning coffee into theorems._" Paul Erdos

> "_Games are won by players who focus on the playing field, not by those whose eyes are glued to the scoreboard._" Warren Buffet

> "_The single most important thing in life is to believe in yourself regardless of what everyone else says._” Hikaru Nakamura

### References

[back to TOC](#table-of-contents)

- [Last repos I starred from GitHub API](https://api.github.com/users/mycaule/starred?page=1&per_page=100)
- [Goodreads Data Export](https://www.goodreads.com/review/import)
- [Pocket Data Export](https://getpocket.com/export)
