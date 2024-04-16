# A-COBIT-2019-Risk-Assessment-Approach
A Risk Assessment software based on COBIT (2019).

**_(Under development/revision)_** Developed using Java, the program, uses an own methodology (based on [this paper](https://github.com/Lucho-A/A-Risk-Assessment-approach-based-on-Information-Theory)) for evaluating and prioritizing COBIT (2019) processes/objectives.

**20240415 Rev. note:** I'm evaluating the approach ([uploaded](https://github.com/Lucho-A/A-COBIT-2019-Risk-Assessment-Approach/blob/master/rm-cobit2019.xlsm), the file I'm using for testing). The idea is eventually incorporate the practices, activities, and the chance to incorporate controls where all this is going to be quite more interesting. In fact, the idea came up for controls, but in order to evaluate the methodology, I just prefered a Top Down approach. Anyway, let's see...

### Some features:
- Because the concept of probability is so much aligned with controls instead of processes, the "inherent" risk associated is only in line with the different impacts of the processes, this is: information impact, financial/economic impact, and others (compliance impact, for example).
- It takes into consideration not only the result of the latest evaluation (in order to evaluate the residual risk) but, also, the aging (the elapsed period) between the date of the latest revision and the current day. <sup>[1](#footnote1)</sup>
- It defines a value (risk exposure) as the quotient between the residual risk and the impact expressed in bits/impact (this is, how much information I have per impact unit. Less value, less information I have and, in consequence, these processes could be considered to be reviewed with highest priority).

It's a client-server program (using SSL) but only for performing login (mainly, for web-service security and performance issues), and for serving the impact and risk exposure values. The program keeps locally the risk map information, and allows export the information in csv format.

##### <sup><a name="footnote1">1</a></sup>: Asumming that the amortization of the engagements is 5 (five) years.

### Usage
~~1) [Download](https://github.com/Lucho-A/A-COBIT-2019-Risk-Assessment-Approach/releases/latest) the zip file. <br>
2) Unzip it wherever you want. <br>
3) Execute the .bat file. <br> <br>
Requirement note: for sure, you must have java installed and into the "PATH" variable (if not, you can edit the .bat for specifying the executable location). The program was tested with Java 17 Eclipse Temurin. You can download it from [here](https://adoptium.net/es/). Plsss, see release descriptions for particular issues.~~

### Feedback
I find the approach interesting, at least, original! hahah I'm not sure whether it will have organizational impact, but is, in first place, an intellectual and theorical approach. So, any comment, bugs or crashes issues, suggestion, or any kind of feedback, it will be appreciated (luis.alfie@gmail.com).

Enjoy!
<p align="center">

<img height="300" src="https://user-images.githubusercontent.com/40904281/211438121-02794fdd-26ad-4a27-b808-c6a82b2158cc.png">

![image](https://user-images.githubusercontent.com/40904281/149053255-35c88746-5628-4526-80d7-e216679ad86f.png)

![javaw_xwi3ZiQ8jl](https://user-images.githubusercontent.com/40904281/149053363-89b8c58b-ea46-482f-a1ca-001d1447efee.png)

![javaw_xvQUDnZZmZ](https://user-images.githubusercontent.com/40904281/149053415-edb90768-55df-4c70-a82b-a42c113edfb3.png)

![javaw_HMIG1lKDL6](https://user-images.githubusercontent.com/40904281/149053444-1cdffb6c-e51b-403e-a79a-718c5b0f2043.png)

</p>


















