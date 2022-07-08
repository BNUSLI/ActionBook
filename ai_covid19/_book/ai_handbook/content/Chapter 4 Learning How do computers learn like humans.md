# Chapter 4 Learning: How do computers learn like humans? ![13](https://img.shields.io/badge/Age-13%2B-9cf)

While humans learn from their past experiences, computers can learn from data rather than through explicit programming. This is known as machine learning. Machine learning uses a variety of algorithms that iteratively learn from data to improve, describe data, and predict outcomes. For instance, as shown in Figure 18, in an online shopping website, the machine will learn the preferences or choices of a particular customer by recording the products that he/she has bought or went through. It will then start recommending to the customer based on these preferences.

<br>
<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);"
    src="https://md.hass.live/ai20.png">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 1px;">Figure 20. A computer learning about a shopper from his data</div>
</center>
<br>

In machine learning, four types of learning could be implemented:

1.**Supervised learning**: In this learning type, the machine learning model is taught some knowledge in advance so it can predict future instances. To simplify this definition, we want the machine to know if the student X is a hardworking, good or lazy student based on: **(1)** how many learning hours he/she spends per day; **(2)** how many hours he/she watches the TV. As we mentioned, we need to first teach the machine; in this case we have to give it previous knowledge (also known as labeled dataset) about other students, as shown in Table 1. As you can see in the knowledge given in Table 1, the type of student is known (hard working, good, lazy). The machine will first learn from this knowledge. It will then classify any new student (for instance, our student X) based on how many hours, he/she spent learning and watching TV.

<center>
<div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 1px;">Table 1. Example of knowledge information (also known as labeled dataset) to classify a student</div>
</center>

Student	| Learning hours | TV watching hours | Type of student
:---: | :---: | :---: | :---:
Adam | 5 | 1 | Hard working
Sarra | 3 | 2 | Good student
Charlie | 2 | 3 | Lazy student

2.**Unsupervised learning**: In this learning type, we do not teach the machine learning model (like in the first case). Hence, the machine will work on unlabeled data and it will classify or cluster this data based on similar patterns or features.

3.**Reinforcement learning**: In this learning type, an agent will be within an interactive environment and in a specific state. It will then learn from its own actions and experiences by trial and error using feedback from the environment. To simplify this, we take the example of “fetch the ball” game between the dog and its owner (See Figure 19). The dog (agent) will be in the garden with its owner (interactive environment) where the owner throws the ball (state). The dog (agent) has to perform an action which could be running after the ball or not. If the dog fetches the ball (action), its owner (interactive environment) will reward him by giving him food, in this way the dog (agent) will know that he is doing the right action and he should keep doing that. If the dog does not bring the ball (action), its owner will not give him food. In this way, the dog (agent) will know that it is doing the wrong action, and it should go bring the ball (correct action)

<br>
<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);"
    src="https://md.hass.live/ai21.png">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 1px;">Figure 21. “Fetch the ball” game between the dog and its owner</div>
</center>
<br>

4.**Deep learning**: Deep learning is a specific method of machine learning that incorporates neural networks in successive layers in order to learn from data in an iterative manner. Deep learning is especially useful when you are trying to learn patterns from unstructured data.

Just like we have seen above, machine learning can learn and make predictions based on the given data. Therefore, it is important to give the machine: **(1)** good quality data: which means accurate and correct data that can help the machine takes correct decisions; and, **(2)** big amount of data which can help the machine learns several information that can help it perform several actions and decisions. To simplify this, we can consider the machine as the “car” and the data as the “fuel” (See Figure 20). So, the car cannot work without the fuel, same for the machine, it cannot work without the data. Also, if we give too much good quality fuel to the car, the engine then will not be harmed and the car can take us on a long trip. Same for the machine, accurate data, will not harm the machine and make it take correct decisions, and too much data will make it take several decisions or predictions.

<br>
<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);"
    src="https://md.hass.live/ai22.png">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 1px;">Figure 22. Importance of data for machine learning</div>
</center>
<br>

| **Computer (/kəmˈpyutər/) data (/ˈdeɪtə, ˈdætə, ˈdɑtə/)**
| ---
| *Computer data is information processed or stored by a computer. This information can be in different forms, such as text, audio, or image. Computer data is processed by the computer's Central Processing Uunit (CPU) and can be stored on the computer's hard disk or online, on the cloud.*

There is an urgent need for hospitals and relevant departments at all levels to establish interactive information interfaces and connections, as well as a platform for all parties to collaborate and share information in real time, so that information and data can be shared among medical institutions and between medical institutions and regional administrative departments in accordance with their mandates, providing an effective basis for management and decision-making. In this context, the most important thing is to provide a unified and structured data platform, so that doctors and researchers can easily access to international and updated data. For instance, as shown in Figure 21, COVID-19 surveillance platform was established by Ningbo medical health committee, China in the early 2020, and it could be used to monitor the 4000 medical institutions in Ningbo. All of the data, such confirmed cases, age of infected patients, etc. come from the Yindu Cloud in China.

<br>
<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);"
    src="https://md.hass.live/ai23.png">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 1px;">Figure 23. COVID-19 surveillance platform, established by Ningbo medical health committee</div>
</center>
<br>
