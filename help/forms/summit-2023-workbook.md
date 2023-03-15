---
title: Build Engaging Forms Using Core Components and Headless
seo-title: Build Engaging Forms Using Core Components and Headless
description: Build Engaging Forms Using Core Components and Headless
seo-description: Build Engaging Forms Using Core Components and Headless
topic-tags: develop
hide: yes
hidefromtoc: yes
---

# Build Engaging Forms Using Core Components and Headless

## Lab Overview

In this hands-on lab, you learn:

How to use AEM Forms to easily create adaptive forms using the latest core components which are consistent with AEM Sites, enable omnichannel data capture experiences by delivering the adaptive forms as headless forms to web, mobile, and chat. You also learn best practices around styling, customizations, and front-end development.

## Key takeaways

*   **Business Agility**: As a business user, I can author Form experience for multiple channels easily.

*   **Power to frontend developer**: As a frontend developer, I can control the end-user experience using headless forms.

*   **Developer Velocity**: As a developer, I can easily and consistently customize Sites and Forms components.

## Prerequisites

*   AEM Forms as Cloud Service sandbox

    <table>
        <thead>
            <tr><th>name</th><th>program id</th><th>environment id</th><th>username</th><th>pipeline trigger on commit</th><th>repository url</th><th>front-end - branch and repo</th><th>front-end repo name</th><th>frontend-pipeline</th><th>link</th><th>program url</th><th>environment listing url</th><th>front-end repo url</th><th>toggles url</th></tr>           
        </thead>
        <tbody>
            <tr><td>L716001</td><td>105303</td><td>986623</td><td>L716+001@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716001-p105303-uk94266/</td><td>yes</td><td>wknd</td><td>yes</td><td>https://author-p105303-e986623.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/105303</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/105303</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wkndtheme</td><td>https://author-p105303-e986623.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716002</td><td>106405</td><td>993047</td><td>L716+002@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716002-p106405-uk30744/</td><td>yes</td><td>wknd2</td><td>yes</td><td>https://author-p106405-e993047.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106405</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106405</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wkndtheme2/</td><td>https://author-p106405-e993047.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716003</td><td>106406</td><td>993049</td><td>L716+003@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716003-p106406-uk82969/</td><td>yes</td><td>wknd3</td><td>yes</td><td>https://author-p106406-e993049.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106406</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106406</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wkndtheme3/</td><td>https://author-p106406-e993049.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716004</td><td>106398</td><td>993114</td><td>L716+004@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716004-p106398-uk62851/</td><td>yes</td><td>wknd4</td><td>yes</td><td>https://author-p106398-e993114.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106398</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106398</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wkndtheme4/</td><td>https://author-p106398-e993114.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716005</td><td>106407</td><td>993048</td><td>L716+005@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716005-p106407-uk76414/</td><td>yes</td><td>wknd5</td><td>yes</td><td>https://author-p106407-e993048.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106407</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106407</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wkndtheme5/</td><td>https://author-p106407-e993048.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716006</td><td>106408</td><td>993155</td><td>L716+006@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716006-p106408-uk98879/</td><td>yes</td><td>wknd6</td><td>yes</td><td>https://author-p106408-e993155.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106408</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106408</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wkndtheme6/</td><td>https://author-p106408-e993155.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716007</td><td>106343</td><td>993067</td><td>L716+007@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716007-p106343-uk17215/</td><td>yes</td><td>wknd7</td><td>yes</td><td>https://author-p106343-e993067.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106343</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106343</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wkndtheme7</td><td>https://author-p106343-e993067.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716008</td><td>106399</td><td>993108</td><td>L716+008@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716008-p106399-uk50450/</td><td>yes</td><td>wknd8</td><td>yes</td><td>https://author-p106399-e993108.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106399</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106399</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wkndtheme8</td><td>https://author-p106399-e993108.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716009</td><td>106344</td><td>993064</td><td>L716+009@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716009-p106344-uk63538/</td><td>yes</td><td>wknd9</td><td>yes</td><td>https://author-p106344-e993064.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106344</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106344</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wkndtheme9/</td><td>https://author-p106344-e993064.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716010</td><td>106409</td><td>993051</td><td>L716+010@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716010-p106409-uk19656/</td><td>yes</td><td>wknd10</td><td>yes</td><td>https://author-p106409-e993051.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106409</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106409</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd10</td><td>https://author-p106409-e993051.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716011</td><td>106345</td><td>993060</td><td>L716+011@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716011-p106345-uk54192/</td><td>yes</td><td>wknd11</td><td>yes</td><td>https://author-p106345-e993060.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106345</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106345</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd11</td><td>https://author-p106345-e993060.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716012</td><td>106346</td><td>993061</td><td>L716+012@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716012-p106346-uk49638/</td><td>yes</td><td>wknd12</td><td>yes</td><td>https://author-p106346-e993061.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106346</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106346</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd12</td><td>https://author-p106346-e993061.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716013</td><td>106410</td><td>993153</td><td>L716+013@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716013-p106410-uk94707/</td><td>yes</td><td>wknd13</td><td>yes</td><td>https://author-p106410-e993153.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106410</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106410</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd13</td><td>https://author-p106410-e993153.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716014</td><td>106502</td><td>993073</td><td>L716+014@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716014-p106502-uk23328/</td><td>yes</td><td>wknd14</td><td>yes</td><td>https://author-p106502-e993073.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106502</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106502</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd14</td><td>https://author-p106502-e993073.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716015</td><td>106401</td><td>993112</td><td>L716+015@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716015-p106401-uk94501/</td><td>yes</td><td>wknd15</td><td>yes</td><td>https://author-p106401-e993112.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106401</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106401</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd15</td><td>https://author-p106401-e993112.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716016</td><td>106452</td><td>993115</td><td>L716+016@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716016-p106452-uk35087/</td><td>yes</td><td>wknd16</td><td>yes</td><td>https://author-p106452-e993115.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106452</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106452</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd16</td><td>https://author-p106452-e993115.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716017</td><td>106453</td><td>993113</td><td>L716+017@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716017-p106453-uk55732/</td><td>yes</td><td>wknd17</td><td>yes</td><td>https://author-p106453-e993113.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106453</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106453</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd17</td><td>https://author-p106453-e993113.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716018</td><td>106411</td><td>993050</td><td>L716+018@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716018-p106411-uk77613/</td><td>yes</td><td>wknd18</td><td>yes</td><td>https://author-p106411-e993050.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106411</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106411</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd18</td><td>https://author-p106411-e993050.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716019</td><td>106454</td><td>993116</td><td>L716+019@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716019-p106454-uk19216/</td><td>yes</td><td>wknd19</td><td>yes</td><td>https://author-p106454-e993116.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106454</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106454</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd19</td><td>https://author-p106454-e993116.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716020</td><td>106347</td><td>993063</td><td>L716+020@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716020-p106347-uk53952/</td><td>yes</td><td>wknd20</td><td>yes</td><td>https://author-p106347-e993063.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106347</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106347</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd20</td><td>https://author-p106347-e993063.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716021</td><td>106455</td><td>993109</td><td>L716+021@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716021-p106455-uk24058/</td><td>yes</td><td>wknd21</td><td>yes</td><td>https://author-p106455-e993109.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106455</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106455</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd21</td><td>https://author-p106455-e993109.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716022</td><td>106456</td><td>993110</td><td>L716+022@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716022-p106456-uk26793/</td><td>yes</td><td>wknd22</td><td>yes</td><td>https://author-p106456-e993110.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106456</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106456</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd22</td><td>https://author-p106456-e993110.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716023</td><td>106466</td><td>993291</td><td>L716+023@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716023-p106466-uk93719/</td><td>yes</td><td>wknd23</td><td>yes</td><td>https://author-p106466-e993291.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106466</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106466</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd23</td><td>https://author-p106466-e993291.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716024</td><td>106413</td><td>993156</td><td>L716+024@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716024-p106413-uk10856/</td><td>yes</td><td>wknd24</td><td>yes</td><td>https://author-p106413-e993156.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106413</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106413</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd24</td><td>https://author-p106413-e993156.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716025</td><td>106348</td><td>993066</td><td>L716+025@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716025-p106348-uk76381/</td><td>yes</td><td>wknd25</td><td>yes</td><td>https://author-p106348-e993066.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106348</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106348</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd25</td><td>https://author-p106348-e993066.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716026</td><td>106414</td><td>993154</td><td>L716+026@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716026-p106414-uk93983/</td><td>yes</td><td>wknd26</td><td>yes</td><td>https://author-p106414-e993154.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106414</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106414</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd26</td><td>https://author-p106414-e993154.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716027</td><td>106349</td><td>993065</td><td>L716+027@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716027-p106349-uk75744/</td><td>yes</td><td>wknd27</td><td>yes</td><td>https://author-p106349-e993065.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106349</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106349</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd27</td><td>https://author-p106349-e993065.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716028</td><td>106415</td><td>993152</td><td>L716+028@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716028-p106415-uk24248/</td><td>yes</td><td>wknd28</td><td>yes</td><td>https://author-p106415-e993152.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106415</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106415</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd28</td><td>https://author-p106415-e993152.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716029</td><td>106350</td><td>993068</td><td>L716+029@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716029-p106350-uk06304/</td><td>yes</td><td>wknd29</td><td>yes</td><td>https://author-p106350-e993068.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106350</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106350</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd29</td><td>https://author-p106350-e993068.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716030</td><td>106351</td><td>993062</td><td>L716+030@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716030-p106351-uk95707/</td><td>yes</td><td>wknd30</td><td>yes</td><td>https://author-p106351-e993062.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106351</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106351</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd30</td><td>https://author-p106351-e993062.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716031</td><td>106417</td><td>993158</td><td>L716+031@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716031-p106417-uk50022/</td><td>yes</td><td>wknd31</td><td>yes</td><td>https://author-p106417-e993158.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106417</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106417</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd31</td><td>https://author-p106417-e993158.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716032</td><td>106418</td><td>993159</td><td>L716+032@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716032-p106418-uk75663/</td><td>yes</td><td>wknd32</td><td>yes</td><td>https://author-p106418-e993159.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106418</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106418</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd32</td><td>https://author-p106418-e993159.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716033</td><td>106503</td><td>993080</td><td>L716+033@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716033-p106503-uk29541/</td><td>yes</td><td>wknd33</td><td>yes</td><td>https://author-p106503-e993080.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106503</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106503</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd33</td><td>https://author-p106503-e993080.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716034</td><td>106457</td><td>993125</td><td>L716+034@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716034-p106457-uk91438/</td><td>yes</td><td>wknd34</td><td>yes</td><td>https://author-p106457-e993125.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106457</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106457</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd34</td><td>https://author-p106457-e993125.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716035</td><td>106504</td><td>993081</td><td>L716+035@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716035-p106504-uk46573/</td><td>yes</td><td>wknd35</td><td>yes</td><td>https://author-p106504-e993081.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106504</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106504</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd35</td><td>https://author-p106504-e993081.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716036</td><td>106458</td><td>993120</td><td>L716+036@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716036-p106458-uk91382/</td><td>yes</td><td>wknd36</td><td>yes</td><td>https://author-p106458-e993120.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106458</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106458</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd36</td><td>https://author-p106458-e993120.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716037</td><td>106419</td><td>993160</td><td>L716+037@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716037-p106419-uk99235/</td><td>yes</td><td>wknd37</td><td>yes</td><td>https://author-p106419-e993160.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106419</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106419</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd37</td><td>https://author-p106419-e993160.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716038</td><td>106420</td><td>993162</td><td>L716+038@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716038-p106420-uk24222/</td><td>yes</td><td>wknd38</td><td>yes</td><td>https://author-p106420-e993162.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106420</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106420</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd38</td><td>https://author-p106420-e993162.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716039</td><td>106517</td><td>993235</td><td>L716+039@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716039-p106517-uk88649/</td><td>yes</td><td>wknd39</td><td>yes</td><td>https://author-p106517-e993235.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106517</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106517</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd39</td><td>https://author-p106517-e993235.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716040</td><td>106506</td><td>993079</td><td>L716+040@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716040-p106506-uk58481/</td><td>yes</td><td>wknd40</td><td>yes</td><td>https://author-p106506-e993079.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106506</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106506</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd40</td><td>https://author-p106506-e993079.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716041</td><td>106507</td><td>993074</td><td>L716+041@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716041-p106507-uk39478/</td><td>yes</td><td>wknd41</td><td>yes</td><td>https://author-p106507-e993074.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106507</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106507</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd41</td><td>https://author-p106507-e993074.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716042</td><td>106508</td><td>993075</td><td>L716+042@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716042-p106508-uk03034/</td><td>yes</td><td>wknd42</td><td>yes</td><td>https://author-p106508-e993075.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106508</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106508</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd42</td><td>https://author-p106508-e993075.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716043</td><td>106421</td><td>993163</td><td>L716+043@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716043-p106421-uk19734/</td><td>yes</td><td>wknd43</td><td>yes</td><td>https://author-p106421-e993163.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106421</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106421</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd43</td><td>https://author-p106421-e993163.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716044</td><td>106459</td><td>993121</td><td>L716+044@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716044-p106459-uk31012/</td><td>yes</td><td>wknd44</td><td>yes</td><td>https://author-p106459-e993121.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106459</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106459</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd44</td><td>https://author-p106459-e993121.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716045</td><td>106467</td><td>993292</td><td>L716+045@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716045-p106467-uk08507/</td><td>yes</td><td>wknd45</td><td>yes</td><td>https://author-p106467-e993292.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106467</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106467</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd45</td><td>https://author-p106467-e993292.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716046</td><td>106518</td><td>993234</td><td>L716+046@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716046-p106518-uk42276/</td><td>yes</td><td>wknd46</td><td>yes</td><td>https://author-p106518-e993234.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106518</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106518</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd46</td><td>https://author-p106518-e993234.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716047</td><td>106511</td><td>993076</td><td>L716+047@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716047-p106511-uk14074/</td><td>yes</td><td>wknd47</td><td>yes</td><td>https://author-p106511-e993076.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106511</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106511</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd47</td><td>https://author-p106511-e993076.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716048</td><td>106512</td><td>993077</td><td>L716+048@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716048-p106512-uk09248/</td><td>yes</td><td>wknd48</td><td>yes</td><td>https://author-p106512-e993077.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106512</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106512</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd48</td><td>https://author-p106512-e993077.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716049</td><td>106460</td><td>993124</td><td>L716+049@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716049-p106460-uk30141/</td><td>yes</td><td>wknd49</td><td>yes</td><td>https://author-p106460-e993124.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106460</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106460</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd49</td><td>https://author-p106460-e993124.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716050</td><td>106519</td><td>993237</td><td>L716+050@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716050-p106519-uk22660/</td><td>yes</td><td>wknd50</td><td>yes</td><td>https://author-p106519-e993237.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106519</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106519</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd50</td><td>https://author-p106519-e993237.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716051</td><td>106513</td><td>993084</td><td>L716+051@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716051-p106513-uk50830/</td><td>yes</td><td>wknd51</td><td>yes</td><td>https://author-p106513-e993084.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106513</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106513</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd51</td><td>https://author-p106513-e993084.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716052</td><td>106461</td><td>993122</td><td>L716+052@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716052-p106461-uk73956/</td><td>yes</td><td>wknd52</td><td>yes</td><td>https://author-p106461-e993122.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106461</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106461</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd52</td><td>https://author-p106461-e993122.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716053</td><td>106514</td><td>993082</td><td>L716+053@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716053-p106514-uk25965/</td><td>yes</td><td>wknd53</td><td>yes</td><td>https://author-p106514-e993082.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106514</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106514</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd53</td><td>https://author-p106514-e993082.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716054</td><td>106462</td><td>993123</td><td>L716+054@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716054-p106462-uk07017/</td><td>yes</td><td>wknd54</td><td>yes</td><td>https://author-p106462-e993123.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106462</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106462</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd54</td><td>https://author-p106462-e993123.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716055</td><td>106463</td><td>993127</td><td>L716+055@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716055-p106463-uk94955/</td><td>yes</td><td>wknd55</td><td>yes</td><td>https://author-p106463-e993127.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106463</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106463</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd55</td><td>https://author-p106463-e993127.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716056</td><td>106515</td><td>993083</td><td>L716+056@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716056-p106515-uk12658/</td><td>yes</td><td>wknd56</td><td>yes</td><td>https://author-p106515-e993083.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106515</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106515</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd56</td><td>https://author-p106515-e993083.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716057</td><td>106464</td><td>993126</td><td>L716+057@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716057-p106464-uk13238/</td><td>yes</td><td>wknd57</td><td>yes</td><td>https://author-p106464-e993126.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106464</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106464</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd57</td><td>https://author-p106464-e993126.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716058</td><td>106520</td><td>993236</td><td>L716+058@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716058-p106520-uk93785/</td><td>yes</td><td>wknd58</td><td>yes</td><td>https://author-p106520-e993236.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106520</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106520</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd58</td><td>https://author-p106520-e993236.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716059</td><td>106423</td><td>993161</td><td>L716+059@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716059-p106423-uk31356/</td><td>yes</td><td>wknd59</td><td>yes</td><td>https://author-p106423-e993161.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106423</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106423</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd59</td><td>https://author-p106423-e993161.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716060</td><td>106516</td><td>993078</td><td>L716+060@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716060-p106516-uk84089/</td><td>yes</td><td>wknd60</td><td>yes</td><td>https://author-p106516-e993078.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106516</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106516</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd60</td><td>https://author-p106516-e993078.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716061</td><td>106521</td><td>993240</td><td>L716+061@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716061-p106521-uk14423/</td><td>yes</td><td>wknd61</td><td>yes</td><td>https://author-p106521-e993240.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106521</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106521</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd61</td><td>https://author-p106521-e993240.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716062</td><td>106424</td><td>993308</td><td>L716+062@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716062-p106424-uk04070/</td><td>yes</td><td>wknd62</td><td>yes</td><td>https://author-p106424-e993308.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106424</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106424</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd62</td><td>https://author-p106424-e993308.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716063</td><td>106468</td><td>993295</td><td>L716+063@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716063-p106468-uk65739/</td><td>yes</td><td>wknd63</td><td>yes</td><td>https://author-p106468-e993295.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106468</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106468</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd63</td><td>https://author-p106468-e993295.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716064</td><td>106425</td><td>993309</td><td>L716+064@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716064-p106425-uk89411/</td><td>yes</td><td>wknd64</td><td>yes</td><td>https://author-p106425-e993309.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106425</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106425</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd64</td><td>https://author-p106425-e993309.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716065</td><td>106426</td><td>993314</td><td>L716+065@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716065-p106426-uk38598/</td><td>yes</td><td>wknd65</td><td>yes</td><td>https://author-p106426-e993314.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106426</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106426</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd65</td><td>https://author-p106426-e993314.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716066</td><td>106469</td><td>993293</td><td>L716+066@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716066-p106469-uk05356/</td><td>yes</td><td>wknd66</td><td>yes</td><td>https://author-p106469-e993293.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106469</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106469</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd66</td><td>https://author-p106469-e993293.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716067</td><td>106522</td><td>993238</td><td>L716+067@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716067-p106522-uk44251/</td><td>yes</td><td>wknd67</td><td>yes</td><td>https://author-p106522-e993238.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106522</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106522</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd67</td><td>https://author-p106522-e993238.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716068</td><td>106470</td><td>993299</td><td>L716+068@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716068-p106470-uk32462/</td><td>yes</td><td>wknd68</td><td>yes</td><td>https://author-p106470-e993299.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106470</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106470</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd68</td><td>https://author-p106470-e993299.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716069</td><td>106427</td><td>993311</td><td>L716+069@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716069-p106427-uk83971/</td><td>yes</td><td>wknd69</td><td>yes</td><td>https://author-p106427-e993311.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106427</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106427</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd69</td><td>https://author-p106427-e993311.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716070</td><td>106428</td><td>993310</td><td>L716+070@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716070-p106428-uk60835/</td><td>yes</td><td>wknd70</td><td>yes</td><td>https://author-p106428-e993310.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106428</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106428</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd70</td><td>https://author-p106428-e993310.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716071</td><td>106471</td><td>993298</td><td>L716+071@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716071-p106471-uk86739/</td><td>yes</td><td>wknd71</td><td>yes</td><td>https://author-p106471-e993298.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106471</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106471</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd71</td><td>https://author-p106471-e993298.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716072</td><td>106429</td><td>993315</td><td>L716+072@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716072-p106429-uk23084/</td><td>yes</td><td>wknd72</td><td>yes</td><td>https://author-p106429-e993315.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106429</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106429</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd72</td><td>https://author-p106429-e993315.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716073</td><td>106523</td><td>993239</td><td>L716+073@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716073-p106523-uk23422/</td><td>yes</td><td>wknd73</td><td>yes</td><td>https://author-p106523-e993239.adobeaemcloud.com/</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106523</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106523</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd73</td><td>https://author-p106523-e993239.adobeaemcloud.com//etc.clientlibs/toggles.json</td></tr><tr><td>L716074</td><td>106472</td><td>993300</td><td>L716+074@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716074-p106472-uk38017/</td><td>yes</td><td>wknd74</td><td>yes</td><td>https://author-p106472-e993300.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106472</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106472</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd74</td><td>https://author-p106472-e993300.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716075</td><td>106430</td><td>993312</td><td>L716+075@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716075-p106430-uk55913/</td><td>yes</td><td>wknd75</td><td>yes</td><td>https://author-p106430-e993312.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106430</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106430</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd75</td><td>https://author-p106430-e993312.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716076</td><td>106524</td><td>993241</td><td>L716+076@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716076-p106524-uk94081/</td><td>yes</td><td>wknd76</td><td>yes</td><td>https://author-p106524-e993241.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106524</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106524</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd76</td><td>https://author-p106524-e993241.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716077</td><td>106431</td><td>993313</td><td>L716+077@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716077-p106431-uk09241/</td><td>yes</td><td>wknd77</td><td>yes</td><td>https://author-p106431-e993313.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106431</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106431</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd77</td><td>https://author-p106431-e993313.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716078</td><td>106473</td><td>993294</td><td>L716+078@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716078-p106473-uk84023/</td><td>yes</td><td>wknd78</td><td>yes</td><td>https://author-p106473-e993294.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106473</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106473</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd78</td><td>https://author-p106473-e993294.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716079</td><td>106474</td><td>993297</td><td>L716+079@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716079-p106474-uk83600/</td><td>yes</td><td>wknd79</td><td>yes</td><td>https://author-p106474-e993297.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106474</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106474</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd79</td><td>https://author-p106474-e993297.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716080</td><td>106475</td><td>993296</td><td>L716+080@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716080-p106475-uk94755/</td><td>yes</td><td>wknd80</td><td>yes</td><td>https://author-p106475-e993296.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106475</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106475</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd80</td><td>https://author-p106475-e993296.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716081</td><td>106476</td><td>993353</td><td>L716+081@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716081-p106476-uk50558/</td><td>yes</td><td>wknd81</td><td>yes</td><td>https://author-p106476-e993353.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106476</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106476</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd81</td><td>https://author-p106476-e993353.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716082</td><td>106525</td><td>993247</td><td>L716+082@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716082-p106525-uk92893/</td><td>yes</td><td>wknd82</td><td>yes</td><td>https://author-p106525-e993247.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106525</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106525</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd82</td><td>https://author-p106525-e993247.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716083</td><td>106526</td><td>993244</td><td>L716+083@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716083-p106526-uk35635/</td><td>yes</td><td>wknd83</td><td>yes</td><td>https://author-p106526-e993244.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106526</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106526</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd83</td><td>https://author-p106526-e993244.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716084</td><td>106527</td><td>993243</td><td>L716+084@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716084-p106527-uk33428/</td><td>yes</td><td>wknd84</td><td>yes</td><td>https://author-p106527-e993243.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106527</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106527</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd84</td><td>https://author-p106527-e993243.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716085</td><td>106477</td><td>993356</td><td>L716+085@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716085-p106477-uk07483/</td><td>yes</td><td>wknd85</td><td>yes</td><td>https://author-p106477-e993356.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106477</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106477</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd85</td><td>https://author-p106477-e993356.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716086</td><td>106478</td><td>993355</td><td>L716+086@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716086-p106478-uk19752/</td><td>yes</td><td>wknd86</td><td>yes</td><td>https://author-p106478-e993355.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106478</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106478</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd86</td><td>https://author-p106478-e993355.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716087</td><td>106528</td><td>993245</td><td>L716+087@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716087-p106528-uk65196/</td><td>yes</td><td>wknd87</td><td>yes</td><td>https://author-p106528-e993245.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106528</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106528</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd87</td><td>https://author-p106528-e993245.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716088</td><td>106432</td><td>993316</td><td>L716+088@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716088-p106432-uk71669/</td><td>yes</td><td>wknd88</td><td>yes</td><td>https://author-p106432-e993316.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106432</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106432</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd88</td><td>https://author-p106432-e993316.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716089</td><td>106529</td><td>993242</td><td>L716+089@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716089-p106529-uk72336/</td><td>yes</td><td>wknd89</td><td>yes</td><td>https://author-p106529-e993242.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106529</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106529</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd89</td><td>https://author-p106529-e993242.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716090</td><td>106436</td><td>993320</td><td>L716+090@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716090-p106436-uk96513/</td><td>yes</td><td>wknd90</td><td>yes</td><td>https://author-p106436-e993320.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106436</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106436</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd90</td><td>https://author-p106436-e993320.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716091</td><td>106480</td><td>993301</td><td>L716+091@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716091-p106480-uk26189/</td><td>yes</td><td>wknd91</td><td>yes</td><td>https://author-p106480-e993301.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106480</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106480</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd91</td><td>https://author-p106480-e993301.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716092</td><td>106530</td><td>993246</td><td>L716+092@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716092-p106530-uk21496/</td><td>yes</td><td>wknd92</td><td>yes</td><td>https://author-p106530-e993246.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106530</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106530</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd92</td><td>https://author-p106530-e993246.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716093</td><td>106481</td><td>993352</td><td>L716+093@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716093-p106481-uk08136/</td><td>yes</td><td>wknd93</td><td>yes</td><td>https://author-p106481-e993352.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106481</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106481</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd93</td><td>https://author-p106481-e993352.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716094</td><td>106482</td><td>993354</td><td>L716+094@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716094-p106482-uk12991/</td><td>yes</td><td>wknd94</td><td>yes</td><td>https://author-p106482-e993354.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106482</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106482</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd94</td><td>https://author-p106482-e993354.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716095</td><td>106531</td><td>993248</td><td>L716+095@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716095-p106531-uk35835/</td><td>yes</td><td>wknd95</td><td>yes</td><td>https://author-p106531-e993248.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106531</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106531</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd95</td><td>https://author-p106531-e993248.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716096</td><td>106483</td><td>993357</td><td>L716+096@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716096-p106483-uk62544/</td><td>yes</td><td>wknd96</td><td>yes</td><td>https://author-p106483-e993357.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106483</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106483</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd96</td><td>https://author-p106483-e993357.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716097</td><td>106433</td><td>993318</td><td>L716+097@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716097-p106433-uk01013/</td><td>yes</td><td>wknd97</td><td>yes</td><td>https://author-p106433-e993318.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106433</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106433</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd97</td><td>https://author-p106433-e993318.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716098</td><td>106532</td><td>993249</td><td>L716+098@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716098-p106532-uk23995/</td><td>yes</td><td>wknd98</td><td>yes</td><td>https://author-p106532-e993249.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106532</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106532</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd98</td><td>https://author-p106532-e993249.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716099</td><td>106434</td><td>993317</td><td>L716+099@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716099-p106434-uk60991/</td><td>yes</td><td>wknd99</td><td>yes</td><td>https://author-p106434-e993317.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106434</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106434</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wknd99</td><td>https://author-p106434-e993317.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr><tr><td>L716100</td><td>106435</td><td>993319</td><td>L716+100@summitlab.us</td><td>yes</td><td>https://git.cloudmanager.adobe.com/summit2023l716/L716100-p106435-uk70663/</td><td>yes</td><td>wknd100</td><td>yes</td><td>https://author-p106435-e993319.adobeaemcloud.com</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/home.html/program/106435</td><td>https://experience.adobe.com/#/@summit2023l716/cloud-manager/environments.html/program/106435</td><td>https://git.cloudmanager.adobe.com/summit2023l716/wkndtheme100</td><td>https://author-p106435-e993319.adobeaemcloud.com/etc.clientlibs/toggles.json</td></tr>
        </tbody>
    </table>

## Lesson 1

### Objective

Familiarize yourself with AEM Forms as a Cloud Service environment.

### Lesson context

In this lesson, you familiarize yourself with AEM Forms as a Cloud Service environment by navigating the user interface.

### Exercise

1.  Open your browser and enter the URL of the Cloud Service author environment. For example:
    [https://author-p105303-e986623.adobeaemcloud.com/ui#/aem/aem/start.html](https://author-p105303-e986623.adobeaemcloud.com/ui%23/aem/aem/start.html)

1.  Log in to the Cloud Service author environment as per the credentials shared. For example:
    Username: [L716+001@summitlab.us](mailto:L716%2B001@summitlab.us) 
    Password: **Adobe123!**

1.  After you are logged in, navigate to the AEM Forms UI. Click **Forms**.

    ![](/help/forms/assets/screenshot2028113829.png)

1.  Click **Forms & Documents**. Dismiss any pop-ups related to preferences or information.

    ![](/help/forms/assets/screenshot2028113929.png)

    All the available forms are displayed.
    
    ![](/help/forms/assets/screenshot2028114029.png)

## Lesson 2

### Objective

Author an adaptive form using the latest core components, configure, and submit the form.

### Lesson context

In this lesson, as a business user, you will author an adaptive form for multiple channels like web, mobile, and chat using adaptive forms authoring with standardized OOTB core components for data capture.

### Exercise

1.  Create a submission endpoint for the form:

    1.  Open <https://requestbin.com/> in a new browser tab.
        ![](/help/forms/assets/screenshot2028114329.png)

    1.  Click **Create a public bin** and copy the endpoint URL.
        ![](/help/forms/assets/screenshot202023-03-0120at206.10.0020pm.png)

1.  Author an adaptive form using the Wizard interface:

    1.  In the browser tab used in Lesson 1, navigate to AEM Forms as Cloud Service web interface and navigate to Forms and Documents.
        ![](/help/forms/assets/screenshot2028114029.png)

    1.  Click **Create** and select Adaptive Form.
        ![](/help/forms/assets/screenshot2028114629.png)

    1.  Select the **Blank with Core Components** template from the template selection screen as shown below:
    ![](/help/forms/assets/screenshot202023-03-0120at206.09.1520pm.png)

    1.  Click the **Style** tab and select the **wknd-theme** theme as shown below:
    ![](/help/forms/assets/screenshot202023-03-0120at206.09.2320pm.png)

    1.  Click the **Submission** tab and select the **Submit to REST end-point** card and specify the public bin in the
    **URL for the POST request** field as shown below:
    ![](/help/forms/assets/screenshot202023-03-0120at206.09.5320pm.png)

    1.  Click **Create**. Specify a name and title to your form. For example, **contactus**. Click **Create**.
     ![](/help/forms/assets/screenshot2028123329.png)

    1.  The adaptive form editor opens. Dismiss any pop-ups or dialogs for preferences or information. Click the components browser on left rail and add the **Footer** component to the bottom of the blank form.
     ![](/help/forms/assets/screenshot2028121929.png)

    1.  The header is part of the adaptive form template. It allows an easy way to provide a consistent header/footer across all adaptive forms. Alternatively, you can also choose to keep it editable in the form - as seen for the Footer component in the next step.

    1.  Add a **Title** component to the middle of the form.
     ![](/help/forms/assets/screenshot2028122129.png)

    1.  Add a **Text Input** component after the title component.
     ![](/help/forms/assets/screenshot2028122329.png)

    1.  Add a **Number Input** component.
     ![](/help/forms/assets/screenshot2028122429.png)

    1.  Add a **Submit Button** component to the form.
     ![](/help/forms/assets/screenshot2028122529.png)

    1.  Click the **Title** component so that **pop-up menu** is displayed. Click the **Edit icon** in the menu to edit the label.
     ![](/help/forms/assets/screenshot2028122629.png)

    1.  Enter `Contact Us` as the title text.
    ![](/help/forms/assets/screenshot2028122829.png)

    1.  Click the **Text Input** component so that the pop-up menu is displayed. Click the **Edit icon** in the menu to edit the label.
    ![](/help/forms/assets/screenshot2028122929.png)

    1.  Enter **Full Name** as field label.
    ![](/help/forms/assets/screenshot2028123029.png)

    1.  Click the **Number Input** component so that the pop-up menu is displayed. Click the **Edit icon** in the menu to edit the label.
    ![](/help/forms/assets/screenshot2028123129.png)

    1.  Enter the **Phone number** as the field label.
    ![](/help/forms/assets/screenshot2028123829.png)


1.  Add validations to form:

    1.  Click the **Phone number** component so that the pop-up menu is displayed. Click the **Wrench icon** in the menu to configure the field.
        ![](/help/forms/assets/screenshot2028123429.png)

    1.  Open the **validations tab**, mark the field **Required**, and click **Done**. The success message is displayed.
        ![](/help/forms/assets/screenshot2028123529.png)
        
        ![](/help/forms/assets/screenshot2028123629.png)

    1.  Click **Preview** to preview the form from an end-user perspective.
        ![](/help/forms/assets/screenshot2028125529.png)

    1.  Fill the form with dummy data
        ![](/help/forms/assets/screenshot2028125629.png)

    1.  Submit the form
        ![](/help/forms/assets/screenshot2028125729.png)

    1.  In the Request bin tab, check the submitted data.
        ![](/help/forms/assets/screenshot2028125829.png)

Now for purpose of the remaining exercise, use a pre-created registration form.

1.  Open AEM Forms management interface, for example, `https://author-p105303-e986623.adobeaemcloud.com/ui%23/aem/aem/forms.html/content/dam/formsanddocuments`, and select the registration form.
    
    ![](/help/forms/assets/screenshot2028115529.png)

1.  Click **Publish**.

    ![](/help/forms/assets/screenshot2028115629.png)
    
    The success message is displayed.

    ![](/help/forms/assets/screenshot2028115729.png)

    The publish URL of the form would be similar to `https://publish-p105303-e986623.adobeaemcloud.com/content/forms/af/registration.html`.

1.  To view the published form replace the program ID (pXXXXXX) and environment ID (eXXXXXX) in the above URL with ID's of your
    environment.

## Lesson 3

### Objective

Update styles using frontend development best practices.

### Lesson context

In this lesson, as a front-end developer, you learn how you can update styling for the previously created adaptive form easily.

### Exercise

Set up local repository of the theme:

1.  Open the Command Prompt or shell with administrator rights:

    ![](/help/forms/assets/screenshot2028115829.png)

1.  On the Command Prompt, use the following command to navigate to **c:\git** folder
    
    ```Shell
    
    cd c:\git
    
    ```

1.  Use the following command to clone the theme frontend code:
    
    ```Shell
    
    git clone -b WKND https://github.com/adobe/aem-forms-theme-canvas

    ```
    

1.  Use the following command in the listed order to navigate to the **aem-forms-theme-canvas** directory and open Visual Studio Code.
    
    ```Shell
    
    cd aem-forms-theme-canvas
    code .

    ```
    
    ![](/help/forms/assets/screenshot2028126029.png)

1.  Select **Trust the authors of all files in the parent folder** and click **Yes, I trust the authors**.

    ![](/help/forms/assets/screenshot2028116229.png)

1.  To render the form hosted on your cloud service publish environment, rename the `env_template` file.  To rename the file, right click the **env_template** file and select the **Rename** option.

    ![](/help/forms/assets/screenshot2028116429.png)

     </br>

    ![](/help/forms/assets/screenshot2028116529.png)

1.  Set the following values for the variables in .env file and save the file:

    *   **AEM_URL**: Specify your cloud service publish environment. For example, `https://publish-p105303-e986623.adobeaemcloud.com/`
    
    *   **AEM_ADAPTIVE_FORM**: Specify the path of the form. For example, if the form path is `/content/forms/af/registration`, the value of this variable would be `registration`.

    ![](/help/forms/assets/screenshot2028116429.png)
    

1.  In the Command Prompt window, run the following command:

    ```Shell

    npm install

    ```

    ![](/help/forms/assets/screenshot2028117029.png)

    >[!NOTE]
    >
    > * If you get a message asking to update npm via the `npm notice Run npm nstall -g npm@9.6.0`command, ignore the message.
    > * Do not run other npm commands unless instructed in the workbook.

1.  Now run the following command to preview the form.
    
    ```Shell
    
    npm run live
    
    ```
    
    ![](/help/forms/assets/screenshot2028117229.png)

    Once the above command is executed, wait for the `webpack compiled` message. The form is displayed in a browser tab.

    >[!NOTE]
    >
    >If you experience a blank screen in browser after executing the `npm run live` command for more than 3-4 minutes, change `localhost` in browser URL to 127.0.0.1 and hit **Enter**. 

    
    ![](/help/forms/assets/screenshot2028115129.png)


1.  In Visual Studio Code, open the `PROJECT\src\site\_variables.scss` file. Notice the `$error` color is a shade of RED.

    ![](/help/forms/assets/screenshot2028120729.png)

1.  In the browser, submit the form to see the Red color in the **First Name** field.

    ![](/help/forms/assets/screenshot2028120829.png)

1.  Set the **$error** color to **#5736eb** and save the file. 

    ![](/help/forms/assets/screenshot2028120729.png)

1.  Refresh the browser and submit the form. Notice error color on the first name field has changed accordingly.
    
    ![](/help/forms/assets/screenshot2028121129.png)

1.  In the Command Prompt, press **CTRL+C**, enter **Y**, and press **Enter** key to terminate the npm process. It is important to stop the npm server so it does not conflict with the next set of exercises.
1.  Close Visual Studio Code and Command Prompt windows.

## Lesson 4

### Objective

Render the form to web/mobile and other interfaces as a headless form.

### Lesson context

In this lesson, as a frontend developer, you will learn how you can render the adaptive form created previously as a headless form using react spectrum design framework.

### Exercise

Setup local repository using react starter project:

1.  Open the Command Prompt using administrator rights.

    ![](/help/forms/assets/screenshot2028115829.png)

1.  On the Command Prompt, use the following command to navigate to **c:\git** folder

    ```Shell
    
    cd c:\git

    ```

1.  Use the following command to clone the adaptive form react starter project:
    
    ```Shell
    
    git clone https://github.com/adobe/react-starter-kit-aem-headless-forms

    ```
    
    ![](/help/forms/assets/screenshot2028117329.png)

1.  Use the following commands in the listed order to navigate to the **react-starter-kit-aem-headless-forms** directory and open Visual Studio Code.

    ```Shell
    
    cd react-starter-kit-aem-headless-forms

    code .

    ```
    
    ![](/help/forms/assets/screenshot2028117529.png)
    

    The Visual Studio Code window opens.

    ![](/help/forms/assets/screenshot2028117429.png)

To render the form hosted on your cloud service publish environment:

1.  Rename the env_template file to .env file. To rename, right-click the **env_template** file and select the **Rename** option. 
    
    ![](/help/forms/assets/screenshot2028117629.png)
    
    ![](/help/forms/assets/screenshot2028117729.png)

1.  Set the following values for the variables in the .env file. After updating variables, save the file.

    *   **AEM_URL**: Specify the URL of the cloud service publish environment. For example, `https://publish-p105303-e986623.adobeaemcloud.com`

    *   **AEM_FORM_PATH**: Specify the path of the adaptive form created in the previous lesson. For example, `/content/forms/af/registration/`

        ![](/help/forms/assets/screenshot202023-03-0820at202.49.1820pm.png)

1.  Open the command window, ensure you are at the react-starter-kit-aem-headless-forms directory, and run the following command:

    ```Shell
    
    npm install
    
    ```

    ![](/help/forms/assets/screenshot2028118029.png)


1.  In the Command Prompt window, run the following command:
    
    ```Shell

    npm start
    
    ```

    ![](/help/forms/assets/screenshot2028118129.png)

    The above command starts a local development server which would render the form definition fetched from AEM in a headless way using the react-spectrum frontend library.

    >[!NOTE]
    >
    > 
    > If you experience a blank screen in browser after executing the `npm start` command for more than 3-4 minutes, change `localhost` in browser URL to 127.0.0.1 and hit **Enter**. 

    ![](/help/forms/assets/screenshot2028118229.png)

Let's check the execution of rules in this headless form:

1.  Select the **Check the box to receive 5% off** option. The subsequent option for applying credit card is disabled.

    ![](/help/forms/assets/screenshot2028126229.png)

1.  Uncheck **Check the box to receive 5% off** to enable the credit card option.

    ![](/help/forms/assets/screenshot2028126329.png)

Let's make changes on the form on the server as a business user and view changes reflected in the headless form automatically.

1.  Open the AEM Forms management interface in the browser. For example, [https://author-p105303-e986623.adobeaemcloud.com/ui#/aem/aem/forms.html/content/dam/formsanddocuments](https://author-p105303-e986623.adobeaemcloud.com/ui%23/aem/aem/forms.html/content/dam/formsanddocuments).

1.  Select the **registration** form and click **Edit.** It opens the form in the adaptive forms editor.

    ![](/help/forms/assets/screenshot2028118529.png)

1.  Select the **Phone number** field and click the **Edit icon (Pencil icon)** in the toolbar. If you are not able to see the pop up toolbar, switch to Edit mode by clicking **Edit** button in top right, left to **Preview** button.

    ![](/help/forms/assets/screenshot2028119629.png)

1.  Change the label to Mobile Number. Click any empty space in the form and the changes made to the form are saved.

      ![](/help/forms/assets/screenshot2028119729.png)

Let's publish the updated form to propagate the changes to publish environment.

1.  In the AEM Forms management interface tab, select the registration form, and click **Unpublish**. If you do not see the **Unpublish** button, skip to step 3 to publish the changes directly.

      ![](/help/forms/assets/screenshot2028119829.png)

1.  Click **Unpublish**. Click **Close** in respective dialog.
    
    ![](/help/forms/assets/screenshot2028119929.png)

    ![](/help/forms/assets/screenshot2028120029.png)


1.  After the browser refreshes, select the registration form and click **Publish**.

    ![](/help/forms/assets/screenshot2028120129.png)


1.  Click **Publish**. Click **Close** in the respective dialog.

    ![](/help/forms/assets/screenshot2028120329.png)
    
    ![](/help/forms/assets/screenshot2028120429.png)

1.  Refresh the browser tab with the headless form displayed. Notice, the Phone number label has changed to Mobile number.

    ![](/help/forms/assets/screenshot2028120529.png)

1.  Open the Command Prompt window that is used to start the **react-starter-kit-aem-headless-forms** project, press **CTRL+C**, then
    enter **Y** and press Enter key to terminate the npm process. It is important to stop the npm server so it does not conflict with the next set of exercises.

1.  Close Visual Studio Code and Command Prompt windows.


## Lesson 5

### Objective

Render the form as a headless form using Google Material UI

### Lesson context

In this lesson, as a front-end developer, you learn how to render the adaptive form created previously as a headless form using Google Material UI.

### Exercise

Setup local repository using Material UI starter project:

1.  Open the Command Prompt using administrator rights.
    
    ![](/help/forms/assets/screenshot2028115829.png)


1.  On the Command Prompt, use the following command to navigate to **c:\git** folder:

    ```Shell

    cd c:\git

    ```

1.  Run the following commands in the listed order to create a folder named mui and navigate to the mui folder using following commands: 

    ```Shell

    mkdir mui

    cd mui
    
    ```

1.  Use the following command to clone the adaptive form react starter project: 

    ```Shell

    git clone -b mui https://github.com/adobe/react-starter-kit-aem-headless-forms

    ```

    ![](/help/forms/assets/screenshot2028126529.png)

1.  Use the following command in the listed order to navigate to the **react-starter-kit-aem-headless-forms** folder and open the code in Visual Studio Code:

    ```Shell

    cd react-starter-kit-aem-headless-forms

    code .

    ```

    ![](/help/forms/assets/screenshot2028126829.png)

To render the form hosted on your cloud service publish environment:

1.  Rename the **env_template** file to **.env** file. To rename, right-click the **env_template** file and select **Rename**.

    ![](/help/forms/assets/screenshot2028126629.png)

1.  Set the following values for the variables in the .env file. After updating variables, save the file. Use the **CTRL + S** switch combination to save the file. 

    *   **AEM_URL**: Specify the URL of the cloud service publish environment. For example, [https://publish-p105303-e986623.adobeaemcloud.com](https://publish-p105303-e986623.adobeaemcloud.com/)

    *   **AEM_FORM_PATH**: Specify the path of the adaptive form created in the previous lesson. For example, /content/forms/af/registration/

        ![](/help/forms/assets/screenshot2028126929.png) 

1.  Open the command window, ensure you are at the **react-starter-kit-aem-headless-forms** directory, and run the following command:

    ```Shell
    
    npm install
    
    ```

    ![](/help/forms/assets/screenshot2028127029.png)

1.  In the Command Prompt window, run the following command:
    
    ```Shell

    npm start
    
    ```

    ![](/help/forms/assets/screenshot2028127129.png)
    
    The command starts a local development server and renders the form definition fetched from AEM in a headless way using the Google
    Material UI frontend library.

    >[!NOTE]
    >
    >If you experience a blank screen in browser after executing the `npm start` command for more than 3-4 minutes, change `localhost` in browser URL to 127.0.0.1 and hit **Enter**. 

    ![](/help/forms/assets/screenshot2028127229.png)

1.  To evaluate the execution of the same business logic in this form rendition: 

    Select **Check the box to receive 5% off**. The subsequent option **Would you like to apply for We.Finance Corporate Credit Card Form?** gets disabled.

    ![](/help/forms/assets/screenshot2028127329.png)

## Lesson 6

### Objective

Create an alternate look and feel of the headless form using Material UI component variations

### Lesson context

In this lesson, as a front-end developer, you learn how to create an alternate representation of different components using Material UI for the adaptive form created previously by the business user.

### Exercise

Update the variation of components in the headless project. To change the variant of the material UI text input component to `OutlinedInput`: 

1.  In Visual Code, navigate to the text input component by opening the `index.tsx` file at `src/components/textinput/index.tsx`.

1.  Add `//` at the beginning of the code line 103. It converts the line to a comment. 

    ```Shell

    //const Cmp = \'outlined\' === appliedCssClassNames ? OutlinedInput: Input;

    ```

1.  Add the following at line 104 to use a different variant of component and save the file. Use the **CTRL + S** switch combination to save the file. 

    ```Shell
    
    const Cmp = OutlinedInput;

    ```

    ![](/help/forms/assets/screenshot2028127629.png)

    It is essential to use correct capitalization for 'OutlinedInput' variant else compilation would fail. The local development environment compilation begins automatically in Command Prompt. Wait until you see the following message

    `webpack 5.75.0 compiled with 3 warnings in 6659 ms` 
    `inside proxy req`
    `setting new origin header`

1.  Refresh the browser, if it does not refresh automatically, to see text input component use a different variant.

    ![](/help/forms/assets/screenshot2028127729.png)

    
    This change happens for end users without any change to form definition at AEM Forms Server and is specific for the headless
    channel under consideration. For example, web channel in this lab.
    
    ![](/help/forms/assets/screenshot2028127529.png)


1.  Close Visual Studio Code and Command Prompt Windows.

## Frequently Asked Questions (FAQs)

+++ Is Adaptive Form wizard available publicly?  

Yes, it available with AEM Forms as Cloud Service.

+++


+++ Are core components available publicly?  

Yes, Adaptive Forms core components are available with AEM Forms as Cloud Service.

+++

+++ Are Headless forms available publicly?  

Yes, Headless forms are available with AEM Forms as Cloud Service.

+++

+++ Do Headless forms require a separate license?  

No, Headless forms use the same licensing value metric, number of form submissions.

+++

+++ Are Core components and Headless forms available with AEM 6.5 Forms?  

Yes, both adaptive forms core components and headless forms are available with AEM Forms 6.5 Service Pack 16 and onwards. 

+++


## Next steps

Now that you have learned how to build adaptive forms and deliver them to multiple channels using headless forms, you should try to put your new skills in action. Have fun and go ahead by creating and delivering exceptional data capture experiences to your end users, where they are, at scale!

## Resources

*   [Adaptive Form core components introduction](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/adaptive-forms/introduction.html)

*   [Create adaptive form using core components](https://experienceleague.corp.adobe.com/docs/experience-manager-cloud-service/content/forms/adaptive-forms-authoring/authoring-adaptive-forms-core-components/create-an-adaptive-form-on-forms-cs/creating-adaptive-form-core-components.html)

*   [Update styling for core component-based AF](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/adaptive-forms-authoring/authoring-adaptive-forms-core-components/create-an-adaptive-form-on-forms-cs/using-themes-in-core-components.html?lang=en)

*   [Headless adaptive forms](https://experienceleague.adobe.com/docs/experience-manager-headless-adaptive-forms/using/overview.html?lang=en)

*   [Using Headless React starter kit](https://experienceleague.adobe.com/docs/experience-manager-headless-adaptive-forms/using/get-started/create-and-publish-a-headless-form.html?lang=en)

