# A-COBIT-2019-Risk-Assessment-Approach
A Risk Assessment approach based on COBIT (2019).

#### (_Under testing_)  ####

Developed using Java, the program, uses an own methodology (based on [this paper](https://github.com/Lucho-A/A-Risk-Assessment-approach-based-on-Information-Theory)) for evaluating and prioritizing COBIT (2019) processes/objectives.

### Some features:
- Because the concept of probability is so much aligned with controls instead of processes, the "inherent" risk associated is only in line with the different impacts of the processes, this is: information impact, financial/economic impact, and others (compliance impact, for example).
- It takes into consideration not only the result of the latest evaluation (in order to evaluate the residual risk) but, also, the aging (the elapsed period) between the date of the latest revision and the current day.
- It defines a value (risk exposure) as the quotient between the residual risk and the impact expressed in bits/impact (this is, how much information I have per impact unit. Less value, less information I have and, in consequence, these processes could be considered to be reviewed with highest priority).

It's a client-server program (using SSL) but only for performing login (mainly, for web-service security and performance issues), and for serving the impact and risk exposure values. The program keeps locally the risk map information, and allows export the information in csv format.

### Usage
1) Downloading the zip file.
2) Unzip it wherever you want.
3) Execute the .bat file.

Requirement note: for sure, you must have java installed and into the "PATH" variable (if not, you can edit the .bat for specifying the executable location). The program was tested with Java 17 Eclipse Temurin. You can download it from [here](https://adoptium.net/es/). Plsss, see release descriptions for particular issues. 

### Feedback
I find the approach interesting, at least, original! hahah I'm not sure whether it will have organizational impact, but is, in first place, an intellectual and theorical approach. So, any comment, bugs or crashes issues, suggestion, or any kind of feedback, it will be appreciated (luis.alfie@gmail.com).

Enjoy!

![image](https://user-images.githubusercontent.com/40904281/149053255-35c88746-5628-4526-80d7-e216679ad86f.png)

![javaw_H99XOjK61d](https://user-images.githubusercontent.com/40904281/149053308-615608c6-48c0-4a07-a557-037fdcf919f1.png)

![javaw_xwi3ZiQ8jl](https://user-images.githubusercontent.com/40904281/149053363-89b8c58b-ea46-482f-a1ca-001d1447efee.png)

![javaw_xvQUDnZZmZ](https://user-images.githubusercontent.com/40904281/149053415-edb90768-55df-4c70-a82b-a42c113edfb3.png)

![javaw_HMIG1lKDL6](https://user-images.githubusercontent.com/40904281/149053444-1cdffb6c-e51b-403e-a79a-718c5b0f2043.png)

![javaw_cZWJENGbGR](https://user-images.githubusercontent.com/40904281/149053489-77d870a7-748b-4e59-b80c-eb236edf3298.png)

![javaw_WdVO2F9jIQ](https://user-images.githubusercontent.com/40904281/149053526-eb8aa718-83a1-47c0-b5c1-8b67eeec4c27.png)



















