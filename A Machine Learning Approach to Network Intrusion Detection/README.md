<h1 align="center">Network Intrusion Detection</h1>

  <p align="center">
  <img src="https://media.istockphoto.com/id/1435905195/vector/sentiment-analysis-different-opinions-various-customer-feedback-good-neutral-and-bad.jpg?s=612x612&w=0&k=20&c=8UwuMS5VI2H_9gudMXXV1ixIZ3YBmW6sLb_qexcLoXQ="
       alt="Customer Sentiments" width="65%" />
</p>


<br>
<h3 align="center"><a href="https://drive.google.com/drive/folders/1ReESGIBmAgzLkY7ynyGF69b4TlI-2VFp?usp=sharing">Dataset Link</a></h3>


 
 Business Overview/Problem

In recent times, SecureTech Solutions Inc. has witnessed a notable surge in ransomware attacks directed towards their esteemed clientele. These attacks have undergone a marked evolution, exhibiting heightened levels of sophistication that frequently bypass conventional security protocols.

 

Beyond the substantial financial jeopardy they present, these incidents also bear the potential to tarnish the longstanding reputation and trustworthiness that SecureTech has diligently cultivated over the years

 

 

This surge in ransomware attacks targeting SecureTech Solutions Inc.'s clients underscores a concerning trend in cybersecurity. The attackers have demonstrated a worrisome level of adaptability, deploying increasingly sophisticated tactics that outpace traditional security measures. Beyond the immediate financial implications, these assaults carry the weighty consequence of eroding the trust and reputation that SecureTech has painstakingly built.

 

As the company continues to grapple with this evolving threat landscape, its unwavering commitment to innovation and expertise remains paramount in safeguarding clients' critical assets and preserving their confidence in the face of such challenges.
Rationale for the Project

    In this age, a lot of crime involves malicious actors infiltrating a system, encrypting critical data, and demanding a ransom for its release. This necessitates the ability to detect ransomware and network intrusion. Here are several key reasons why network intrusion detection is crucial:

     
        ✓ Preventing Financial Losses: Network intrusion almost always precede ransomware attacks, which can lead to substantial financial losses, not only from the ransom payment itself but also from the potential downtime, loss of productivity, and the costs associated with recovery and restoration efforts.
         
        ✓ Safeguarding Sensitive Data: Many organizations store highly sensitive and confidential information. Intrusive attacks can result in the exposure or theft of this data, which can have severe legal, financial, and reputational consequences.
         
        ✓ Preserving Business Continuity: Ransomware attacks can disrupt operations, leading to downtime that can be detrimental to an organization's productivity and profitability. Effective detection enables swift response, minimizing disruption and ensuring continuity.
         
        ✓ Maintaining Customer Trust: Successful intrusion attacks can erode the trust that clients and customers have in an organization's ability to protect their data. Detecting and mitigating these threats helps in preserving trust and reputation.
         
        ✓ Compliance and Regulatory Requirements: Many industries and jurisdictions have stringent data protection and privacy regulations. Detecting network attacks promptly and effectively is crucial for compliance with these legal obligations.
         
        ✓ Avoiding Legal Consequences: In some cases, organizations may face legal repercussions if they are unable to adequately protect sensitive data. Prompt intrusion detection helps in mitigating legal risks and liabilities.
         
        ✓ Staying Ahead of Evolving Threats: Intrusion tactics are constantly evolving, becoming more sophisticated and harder to detect. Implementing robust detection measures ensures that organizations can keep pace with these changes and defend against new attack vectors.

Aim of the Project

    ✓ Develop an Effective Network Intrusion Detection System: Create a machine learning model capable of accurately detecting ransomware attacks in real-time.

 

    ✓ Minimize False Positives and False Negatives: Implement algorithms and techniques to reduce false alarms and improve the efficiency of security projections.

 

    ✓ Ensure explainable predictions: Develop a machine learning model which is explainable and can give insights to cyber analysts as regards the fundamentals underlying malware attacks.

Data Description

 

    ✓ Src_Port: Originating port for connection
    ✓ Dst_Port: Destination port for connection
    ✓ Protocol: Connection protocol (HTTP, HTTPS, UDP, TCP etcetera)
    ✓ Flow_Duration: Duration of connection
    ✓ Tot_Fwd_Pkts: Total number of packets transmitted forward over connection lifetime
    ✓ Tot_Bwd_Pkts: Total number of packets transmitted backward over connection lifetime
    ✓ TotLen_Fwd_Pkts: Total size of packets transmitted forward over connection lifetime
    ✓ TotLen_Bwd_Pkts: Total size of packets transmitted backward over connection lifetime
    ✓ Fwd_Pkt_Len_Max: Size of largest packet transmitted forward over connection lifetime
    ✓ Fwd_Pkt_Len_Min: Size of smallest packet transmitted forward over connection lifetime
    ✓ Fwd_Pkt_Len_Mean: Mean size of packets transmitted forward over connection lifetime
    ✓ Fwd_Pkt_Len_Std: Standard deviation of size of packets transmitted forward over connection lifetime
    ✓ Bwd_Pkt_Len_Max: Size of largest packet transmitted backward over connection lifetime
    ✓ Bwd_Pkt_Len_Min: Size of smallest packet transmitted backward over connection lifetime
    ✓ Bwd_Pkt_Len_Mean: Mean size of packets transmitted backward over connection lifetime
    ✓ Bwd_Pkt_Len_Std: Standard deviation of size of packets transmitted backward over connection lifetime
    ✓ Flow_Byts/s: Overall connection speed in bytes per second
    ✓ Flow_Pkts/s: Overall connection speed in number of packets per second
    ✓ Flow_IAT_Mean: Average flow interarrival time
    ✓ Flow_IAT_Std: Standard deviation of flow interarrival time
    ✓ Flow_IAT_Max: Maximum interarrival time recorded for flow
    ✓ Flow_IAT_Min: Minimum interarrival time recorded for flow
    ✓ Fwd_IAT_Tot: Total interarrival time recorded for forward flow
    ✓ Fwd_IAT_Mean: Average flow interarrival time for forward flow
    ✓ Fwd_IAT_Std: Standard deviation of flow interarrival time for forward flow
    ✓ Fwd_IAT_Max: Maximum interarrival time recorded for forward flow
    ✓ Fwd_IAT_Min: Minimum interarrival time recorded for forward flow
    ✓ Bwd_IAT_Tot: Total interarrival time recorded for backward flow
    ✓ Bwd_IAT_Mean: Average flow interarrival time for backward flow
    ✓ Bwd_IAT_Std: Standard deviation of flow interarrival time for backward flow
    ✓ Bwd_IAT_Max: Maximum interarrival time recorded for backward flow
    ✓ Bwd_IAT_Min: Minimum interarrival time recorded for backward flow
    ✓ Bwd_PSH_Flags: PSH flag raised during backward transmission?
    ✓ Fwd_Header_Len: Size of header for forward packets.
    ✓ Bwd_Header_Len: Size of header for backward packets.
    ✓ Fwd_Pkts/s: Forward connection speed in number of packets per second
    ✓ Bwd_Pkts/s: Backward connection speed in number of packets per second
    ✓ Pkt_Len_Min: Size of smallest packet transmitted over connection lifetime
    ✓ Pkt_Len_Max: Size of largest packet transmitted over connection lifetime
    ✓ Pkt_Len_Mean: Mean packet size over connection lifetime
    ✓ Pkt_Len_Std: Standard deviation of packet sizes over connection lifetime
    ✓ Pkt_Len_Var: Variance of packet sizes over connection lifetime
    ✓ FIN_Flag_Cnt: Number of FIN flags raised over connection lifetime.
    ✓ SYN_Flag_Cnt: Number of SYN flags raised over connection lifetime.
    ✓ RST_Flag_Cnt: Number of RST flags raised over connection lifetime.
    ✓ PSH_Flag_Cnt: Number of PSH flags raised over connection lifetime.
    ✓ ACK_Flag_Cnt: Number of ACK flags raised over connection lifetime.
    ✓ Down/Up_Ratio: Ratio of download to upload.
    ✓ Pkt_Size_Avg: Average packet size over entire connection lifetime
    ✓ Fwd_Seg_Size_Avg: Average size of forward packet segments over connection lifetime
    ✓ Bwd_Seg_Size_Avg: Average size of backward packet segments over connection lifetime
    ✓ Subflow_Fwd_Pkts: Number of forward packets in connection subflow
    ✓ Subflow_Fwd_Byts: Number of forward bytes in connection subflow
    ✓ Subflow_Bwd_Pkts: Number of backward packets in connection subflow
    ✓ Subflow_Bwd_Byts: Number of backward bytes in connection subflow
    ✓ Init_Bwd_Win_Byts: Number of backward packets sent in initial connection window
    ✓ Fwd_Act_Data_Pkts: Number of packets with at least 1 byte of TCP data payload in the forward direction
    ✓ Active_Mean: Average packet/connection active time
    ✓ Active_Std: Standard deviation of packet/connection active time
    ✓ Active_Max: Maximum packet/connection active time
    ✓ Active_Min: Minimum packet/connection active time
    ✓ Idle_Mean: Average packet/connection idle time
    ✓ Idle_Std: Standard deviation of packet/connection idle time
    ✓ Idle_Max: Maximum packet/connection idle time
    ✓ Idle_Min: Minimum packet/connection idle time

Tech Stack

The programming language of use, as in most of ML, is Python.

The Python libraries of interest for this project are:

    ✓ NumPy: Numerical computation 
    ✓ Pandas: Data munging and manipulation
    ✓ Matplotlib and Seaborn: Data Visualization
    ✓ PySpark: Parallelized and Distributed Machine Learning

Project Scope

✓ Exploratory Data Analysis: The data is thoroughly explored and analysed to gain insights and understand its characteristics. This involves statistical analysis, data visualization, and other exploratory techniques to identify patterns, correlations, anomalies, and potential issues in the data.

 

✓ Feature Selection: Not all features provided in data may be of relevance to the target. Feature selection is the process by which we can select the most appropriate of these according to a specified set of criteria.

 

✓ Model Development: Various modeling techniques are applied to the prepared data in this stage to build predictive or descriptive models. This can include machine learning algorithms, statistical models, or other analytical approaches. The models are trained, validated, and fine-tuned to optimize their performance.

 

✓ Model Evaluation and Selection: Once the models are developed, they are evaluated using appropriate evaluation metrics and validation techniques. This involves assessing their performance, generalizability, and robustness. The best-performing model(s) are selected for further deployment or refinement.









































<br>
<h1 align="left">Business Problem Overview</h1>
<p align="left">

TechTrends E-commerce Solutions, although a thriving player in the e-commerce sector, faces the challenge of efficiently processing and deriving valuable insights from the substantial influx of customer feedback and reviews it receives on a daily basis. The company's overarching goal is to enhance customer satisfaction and continually refine its product and service offerings. To achieve this, TechTrends E-commerce Solutions seeks to address the following specific business problems:

    A. Managing Feedback Overload: The company struggles with managing the sheer volume of customer feedback effectively. The influx of reviews from its extensive customer base is overwhelming and requires a streamlined approach to handle efficiently.
     
    B. Improving Sentiment Classification: TechTrends aims to enhance the accuracy of sentiment classification for customer feedback. Currently, the categorization of feedback into positive, negative, or neutral sentiments is not as precise as desired. Improving this classification process is crucial for extracting more meaningful insights.

    C. Resource Allocation Optimization: Manual analysis of customer feedback is resource-intensive and time-consuming. TechTrends E-commerce Solutions seeks to reduce these manual efforts through automation to allocate resources more effectively and efficiently.
</p>


<br>
<h1 align="left"> Project Rationale </h1>
<p align="left">
Sentiment analysis is a crucial tool in the field of natural language processing and data analytics. It involves the process of automatically determining the sentiment or emotional tone conveyed in a piece of text, whether it's positive, negative, or neutral.

Sentiment Analysis holds paramount importance in the business landscape. It enables a profound understanding of customer perceptions, driving buisness decisions. By decoding customer sentiment, businesses can swiftly address concerns, enhance satisfaction, and remain competitive. It also aids in identifying areas for improvement, managing brand reputation proactively, and streamlining operations.

Several Reasons accentuate the significance of sentiment analysis. It promotes customer satisfaction by resolving issues promptly and offers insights into competitors. Furthermore, it aids in product enhancement, safeguards brand reputation, and boosts operational efficiency through automation.
</p>


<br> 
<h1 align="left">Aim of the Project </h1>
<p> > Firstly, we aim to develop a sentiment analysis model using NLP techniques, allowing us to effectively classify customer feedback into positive and negative categories. 

> Secondly, we focus on implementation and performance comparison of sentiment analysis tools like NLTK and VADER.

> In tandem, we aim to provide real-time sentiment analysis results to relevant teams, enabling prompt action. Simultaneously, we're committed to extracting actionable insights from sentiment data to drive improvements in customer service and product quality. Ultimately, our overarching objective is to proactively address customer concerns and feedback, thereby enhancing the overall customer experience
</p> 

 
<br>  
<h1 align="left">About The Dataset </h1>
<p> The e commerce company has collected over 3 million reviews. Our dataset is composed of:
 
    A. Customer comments or reviews
    B. Sentiment labels (positive(label 2), negative(label 1)) for model training
We can utilize the customer comments or reviews as the input data and the sentiment labels (positive or negative) as the target variable to train a sentiment analysis model.
</p>


<br>
<h1>Project Scope </h1>
<p>
 
    A. Data Collection: Gather customer feedback from various platforms and sources
    B. Data Preprocessing: Data Preprocessing is a vital preliminary step where we clean and refine raw text data. Techniques like tokenization and stop word removal ensure data readiness for sentiment analysis and model development.
    C. Sentiment Analysis Model Development: We create sentiment analysis models using NLP with NLTK and VADER libraries. These models accurately classify customer feedback sentiments, yielding profound insights.
    D. Model Comparison: Post-model development, we rigorously compare performance metrics like accuracy, precision, recall, and F1-score to select the most effective model for our application.
</p>


<br>
<h1 align="left">Tech Stack</h1>
<p>Programming Language: Python
<p>Libraries :
 
    A. NLTK: For natural language processing and sentiment analysis
    B. VADER: For sentiment analysis
    C. Pandas: For data analysis and manipulation
    D. Scikit-learn: For machine learning
</p>

