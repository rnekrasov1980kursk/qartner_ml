# Конспект отчёта Гартнер по платформам машинного обучения и науки о данных (февраль 2020г.)
Источник: https://www.gartner.com/doc/reprints?__hstc=186155446.ea4b78ea33a1ba46181d31185f00d13f.1582022150723.1582022150723.1582022150723.1&__hssc=186155446.1.1582022150725&id=1-1YDVU5QD&ct=200217&st=sb&submissionGuid=349ddaa7-9c17-470d-8fa3-370c1cd29a21


Получение источников, сборка моделей, операционализация инсайтов машинного обучения  
*Рынок быстро развивается*  
Аналитический конвейер:  
Data ingestion  
Data preparation  
Data exploration  
Feature engineering  
Model creation and training  
Model testing  
Deployment  
Monitoring  
Maintenance  
Collaboration  

Прогнозирующие и предписывающие модели  
##### Кодирование моделей в R и Пайтоне, визуализация конвейеров, autoML  
Демократизация машинного обучения  
Границы между ролями и инструментами продолжают стираться  
Мы признаем устоявшуюся тенденцию коммерческих платформ, использующих компоненты и библиотеки с открытым исходным кодом    
Лучшие элементы из быстро меняющегося ландшафта алгоритмов и технологий  
Платформы должны поддерживать не только построение моделей, но и их ввод в эксплуатацию  
Полная польза,включая ценность для бизнеса, DSML не будет достигнута, если не будут использоваться обе модели:  
1. Встроенные в бизнес-процессы и среду принятия решений  
2. Поддерживается, контролируется и управляется с течением времени  
Облегчить сотрудничество и своевременную доставку стоимости  
Они должны понимать природу рынка DSML и то, чем он отличается от рынка аналитики и бизнес-аналитики (BI) и в чём дополняет его  
Вспомогательный состав имеет жизненно важное значение для масштабирования операций и обеспечения качества данных и постоянной точности модели  
В отчёте приведена подробная ролевая модель дата-команд внутри организации  
![alt text](https://github.com/rnekrasov1980kursk/qartner_ml/blob/master/2020-02-19_1005.png)

Описание сильных и слабых сторон вендоров Altair, Alteryx  
Anaconda стремится к очень большому и активному сообществу пользователей с открытым исходным кодом и корпоративных пользователей, чьи потребности являются важной движущей силой инноваций 
В последнее время Anaconda еще больше улучшила свою масштабируемость  
Улучшение поддержки безопасности и развертывания графических процессоров (GPU) являются другими заметными улучшениями    
Масштабируемость Anaconda использует несколько форм. Пользователи могут масштабировать рабочие нагрузки с помощью GPU и использовать кластеры Apache Hadoop, Apache Hadoop YARN или Kubernetes, локально или в облаке  
Недостаток. В среде Anaconda наблюдается отставание в таких возможностях, как автоML, MLOps и интерпретируемость. Новички Anaconda будут иметь трудности в поиске пути через "джунгли" Python  
Платформа Databricks продолжает вносить свой вклад в сообщество разработчиков с открытым исходным кодом, возглавляя MLflow, Delta Lake и Koalas  
Платформа Databricks обеспечивает масштабируемость развертывания моделей ML, рабочих процессов ML на базе ноутбуков, автоматизацию заданий и управление инфраструктурой данных и трубопроводов. Эталонным клиентам особенно понравилось простое и масштабируемое управление кластерами  
Платформа унифицированного анализа данных Databricks Unified Data Analytics Platform имеет относительно низкий барьер для входа для специалистов по данным и инженеров по данным, имеющих опыт в области кодирования  
Многие клиенты выбирали Databricks не потому, что они искали платформу DSML, а потому, что их интересовали опции для выполнения Apache Spark. У этих клиентов был Hadoop или озеро данных на Amazon Web Services или на Microsoft Azure, и они рассматривают DataBricks как платформу обработки данных, где ML находится в фоновом режиме. Компании, которые не заинтересованы в Spark, часто не рассматривают Databricks как вариант платформы DSML.
Dataiku,DataRobot,Domino  
Google имеет один из крупнейших стеков ML в отрасли  
Сюда входит аппаратное обеспечение, первоклассная среда глубокого обучения (TensorFlow), мощные AI API  и массивная инфраструктура исполнения в облаке  
Google позиционируется как визионер в этом волшебном квадранте  
Для разработчиков Google Cloud AI Platform предлагает фреймворк массового исполнения - Google Cloud Platform (GCP) - и множество различных способов разработки моделей ML (Cloud AutoML, TensorFlow, BigQuery ML, Kubeflow, Notebooks и разнообразные варианты с открытым исходным кодом). Google имеет мощный портфель AI API (от текста, аудио и изображений до обработки видео) и многочисленные первоклассные пакеты для крупномасштабной обработки данных и интеграции (например, BigQuery и Data Fusion)  
автомасштабирование кластера Google Kubernetes Engine (GKE)   
Google Cloud также предлагает мощную поддержку потоковой передачи данных с помощью Cloud Dataproc и Cloud Dataflow  
H2O4GPU  
*H2O.ai служит примером обеспечения богатых функциональных возможностей интерпретации моделей, используя различные методики, такие как K-LIME, LIME-SUP, Shapley, переменная важность, суррогат дерева решений, ICE, графики частичных зависимостей, разрозненный анализ влияния и анализ "что-если"*
H2O.ai, похоже, не отдает предпочтение дополнительным и альтернативным методам, необходимым для IoT или автоматизации принятия решений, таким как обработка потоков, анализ графиков, геопространственный анализ, дискретно-событийное или агенто-ориентированное моделирование, проектирование экспериментов по оптимизации и управление решениями  
IBM, KNIME, MathWorks (MATLAB)  
Портфель продуктов Microsoft, поддерживающих Azure ML, включает Azure Machine Learning Studio, Azure Data Factory, Azure HDInsight, Azure Databricks, Power BI и другие компоненты. Для локальных рабочих нагрузок Microsoft предлагает Machine Learning Server  
RapidMiner,SAS,TIBCO Software
Predictive Model Markup Language (PMML)
Какие возможности предоставляет платформа для мониторинга и перекалибровки сотен или тысяч моделей? Это включает в себя возможности тестирования моделей, такие как k-валидация,train-validation-test-splits, area under the curve (AUC), receiver operating characteristic (ROC), loss matrices, as well as testing models side by side (for example, champion-challenger (A/B) testing)
Дополнительные платформы:  
Amazon SageMaker  
Cloudera Machine Learning (Cloudera Data Science Workbench)  
FICO  
Iguazio  
Oracle Machine Learning  
SAP Data Intelligence  
Teradata Vantage  
World Programming (WPS Analytics)  







