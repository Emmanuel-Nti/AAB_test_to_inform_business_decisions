# A/A/B Test to Inform Business Decisions

### For better view of graphs, click 👉 [a/a/b_testing project](https://nbviewer.jupyter.org/github/Emmanuel-Nti/aab_testing/blob/master/AAB_testing.ipynb)


| Project Description | Libraries Used | Source of Data |
| :---------------------- | :---------------------- | :---------------------- | 
| I work at a startup that sells food products. I need to investigate user behavior for the company's app. I would first study the sales funnel; find out how users reach the purchase stage, how many users actually make it to this stage? how many get stuck at previous stages? which stages in particular? I would then conduct an A/A/B test. The designers would like to change the fonts for the entire app, but the managers are afraid the users might find the new design intimidating. They decide to make a decision based on the results of the A/A/B test. | *pandas*, *matplotlib.pyplot*, *matplotlib.pyplot*, *scipy*, *plotly*, *seaborn*, "numpy*, *math* | Practicum by Yandex |


## Description of Data
**Each log entry is a user action or an event.**
- `EventName:` Event name
- `DeviceIDHash:` Unique user identifier
- `EventTimestamp:` Event time
- `ExpId:` Experiment number: 246 and 247 are the control groups, 248 is the test group
