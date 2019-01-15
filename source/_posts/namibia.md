---
title: KUDU - Namibian Birth/Death Registration App
cover_image: ../images/kudu.png
date: 2019-01-03 00:48:13
type: "Portfolio"
tags:
---

### Background
The birth and death registration process in Namibia is outdated, time-consuming, bureaucratic and according to many Namibians cumbersome. The data is unreliable and contains loopholes since it is easier and cheaper to obtain a new birth certificate than to apply for a duplicate copy. 

The distance within the rural areas to any of the authorized Regional Offices conducting the registration process, as well as the lack of electricity and data network infrastructure in those areas are facts declining the credibility of current CRV system since people within rural areas are neglecting the registration of death or birth.

The Namibian Government’s 2030 strategy declined “war-against-poverty” and it explicitly recognizes the birth and death registration process improvement as a step to reduce the poverty. The overall goals of Namibia NDP4 Strategy 2030 have been defined as 
    - high and sustainable economic growth
    - increased income equality
    - employment creation

As a solution to the above problems, we introduce a new value proposition that invites an entrepreneurial mindset by building a new “Namibian Registrar Service Partner Ecosystem” that provide authorized and trusted registrars to handle the registrations of birth and death within the rural areas. This Ecosystem encourages new Startups opportunities that invite entrepreneurship and increase income equality, employment creation and high sustainable economic growth for.

<img src = "/images/value.png" alt="Value Proposition" style = "height: 500px; width: 700px " class = "center"/>

The value proposition is to create a new partner ecosystem that can execute the registration process of birth and death within the rural areas with the assistance of new technologies like LPWAN, KUHA Mobile Network, and Android App. 

The purpose of this new service is to create opportunities for new entrepreneurs, remove poverty, increase economic growth and help Namibia to transformation towards a more digital society.
 
The reason why this solution suggests LPWAN as a complementary component to the KUHA Mobile Network is that it requires less support and less electricity, which therefore can provide a sustainable solution within the rural areas of Namibia.

### KUDU APP
I was responsible for designing the birth registration flow.

1. Registration process
The birth registration process is quite straightforward. Before the registration starts, the registrar will check if the newborn exists. Then, the registrar follows the steps and fill in the form. All the input fields are mandatory to be filled. Importantly, the newborn will get the E-ID after registering the birth successfully.

2. Use case
The registrar is the only operator in the birth registration stage. When a Namibian citizen come to the registrar and require to register a baby, the registrar is responsible for filling the birth registration form in the app, inputting the correct information and submitting it successfully.

<img src = "/images/use-case.png" alt="Essential Use Case" style = "height: 400px; width: 500px " class = "center"/>

The prototypes of birth registration is a series of forms waiting to be filled. Here are the key prototypes in the birth registration process below, along with the detailed description.

1. Landing stepper
The landing page of birth registration is a stepper, which displays the whole progress of the registration. It is also the first page the user would be navigated, right after the registrar taps the birth registration from the home page. 

    The stepper would show up once the user chose to do the birth registration. It indicates the progress of registration to make sure the user has overview of registration process. There is also a short description of each step to illustrate what the user is going to fill in.

<img src = "/images/kudu1.png" alt="Stepper" style = "height: 450px; width: 520px " class = "center"/>

2. Forms
As the previous stepper displays, the forms of birth registration are divided into four parts: Details of the child, Birth registration details, biological father information, and biological mother information. Separating a length form into clear sections helps reduce users’ short-term memory and decrease the possibility of overwhelming users. Furthermore, the registrar is able to save the form at each step so as not to lose any important information and do repetitive work. It improves the efficiency of registration and prevents accidental application crash. The headline always indicates the current step. Once the form is completed, the button at the bottom right is available to save the contents and continue to the next step.

<img src = "/images/kudu2.png" alt="Forms" style = "height: 600px; width: 900px " class = "center"/>

3. Confirmation and completion
As the last part of the form submission, we designed a confirmation step before they officially submit the form. This is to ensure the user double checks all input information. The confirmation page follows the same pattern as the first land page -- stepper, which ensure the consistency of the whole user journey. 

    Specifically, as the following prototypes shows, there is an ‘edit’ button available in the end of each form section. We offer a shortcut for users to modify their information on this page. 

    After the user verified all information, there will be a pop up dialog window to yield closure. This is to ask user for confirming his action again and also indicate the form will upload formally. There is no chance to change it anymore after this.

    Finally, with a big tick symbol and big size of ‘Congratulations’, this indicates user the completion of the birth registration, which is the last step of the whole progress. What’s more, there is a button of ‘new birth registration’ to give the user a shortcut starting a new registration. The birth registration would be uploaded to the CRV system.

<img src = "/images/kudu3.png" alt="Confirmation" style = "height: 400px; width: 700px " class = "center"/>

Here is a video of the complete design of the [KUDU App](https://drive.google.com/open?id=1dUuj3HmGiGWqMmFRan7bI24sHMI3abc0).

 <div>
    <button onclick="window.location.href = '/index.html';">Back</button>
</div>