## Personalized News Recommendation Based on Click Behavior - Implementation

**Note**: This project is based on the research paper titled **"Personalized News Recommendation Based on Click Behavior" and is written by Jiahui Liu, Peter Dolan, and Elin Rønby Pedersen, 
Address:
Google Inc.
1600 Amphitheatre Parkway, Mountain View, CA 94043, USA
{jiahui, peterdolan, elinp}@google.com**

In no way do we aim to claim that the idea of the research paper is originally ours (either partially or completely) and that we should receive any sort of benefits that the authors of the paper are entitled to. This is a project that is inspired by the paper and is a working model of the same. However, we have used some elements from the research paper in this file for purposes pertaining solely to a better explanation.

The original paper is: [PersonalizedNewsRecommendation.pdf](https://github.com/vishalburman/Recommender_Engine_Google/files/2313475/35599.pdf)

-----------------------------------------------------------------------------------

The generalized approaches that we utilized revolve around the following equations:

- **Click distribution**
1. ![aaa](https://user-images.githubusercontent.com/23614555/44513168-3a89f080-a6da-11e8-810a-76162dd4c012.PNG)

- **Changes in user's news interests over time (graphical representation)**
2. ![aab](https://user-images.githubusercontent.com/23614555/44513170-3cec4a80-a6da-11e8-9012-c2970f7e74a3.PNG)

- **Predicting user's genuine news interests**
3. ![aac](https://user-images.githubusercontent.com/23614555/44513171-3d84e100-a6da-11e8-9012-69a238578f07.PNG)

- **Combining predictions of past time periods**
4. ![aad](https://user-images.githubusercontent.com/23614555/44513172-3d84e100-a6da-11e8-8c7e-da534216d20b.PNG)
5. ![aae](https://user-images.githubusercontent.com/23614555/44513173-3e1d7780-a6da-11e8-8e48-786ac0c4822a.PNG)

- **Predicting user's current news interests**
6. ![aaf](https://user-images.githubusercontent.com/23614555/44513174-3e1d7780-a6da-11e8-93ea-ef77eeb41a26.PNG)
7. ![aag](https://user-images.githubusercontent.com/23614555/44513175-3e1d7780-a6da-11e8-95a1-39ac9e9763e7.PNG)
8. ![aah](https://user-images.githubusercontent.com/23614555/44513176-3eb60e00-a6da-11e8-8f83-2d3b7b92240c.PNG)
9. ![aai](https://user-images.githubusercontent.com/23614555/44513167-3a89f080-a6da-11e8-84b1-ae99647e92c8.PNG)

- **Derived average interests**
10. ![aaj](https://user-images.githubusercontent.com/23614555/44513773-f5ff5480-a6db-11e8-9a96-3231d894a1bd.png)

-----------------------------------------------------------------------------------
