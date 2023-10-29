<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>




<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a >
    <img src="/Users/thian/Desktop/stoke-frontend-student/src/img/icon.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Fullstack ER-tracking</h3>

  <p align="center">
    Tracking application for the ER stroke process
    <br />
    <a href="https://github.com/phurin2644/front-test.git"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://fsd-ertrack.cpe.eng.cmu.ac.th/">View Demo</a>
    ·
  </p>
</div>





<!-- ABOUT THE PROJECT -->
## About The Project

ปัจจุบันการรักษาโรคหลอดเลือดในสมองสามารถรักษาได้อย่างมีประสิทธิภาพมากแล้ว แต่ส่วนหลักๆที่ทำให้อัตราการรอดชีวิตสูงขึ้นมากที่ที่สุดนั่นคือระยะเวลาระหว่างช่วงแสดงอาการและการได้รับการรักษา ในปัจจุบันโรงพยาบาลสวนดอกมีการติดตามขั้นตอนการดำเนินงานโดยใช้ระบบการจด ทำให้ข้อมูลเกิดความไม่ต่อเนื่อง ล่าช้า และอาจตกหล่น ระหว่างกระบวนการได้

เราจึงพัฒนา:
* Web Application ที่ช่วยในการจัดการผู้ป่วยสำหรับพยาบาลภายในห้องฉุกเฉิน เพื่อที่จะทำการจัดการ ติดตาม การรักษาของคนไข้ อย่างเป็นระบบ

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

ในส่วนของ Front-end เราได้ใช้เทคโนโลยีต่อไปนี้
* [![Vite][Vite.js]][Vite-url]
* [![Mantine][Mantine]][Mantine-url]
* [![React-Flow][Reactflow]][Reactflow-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

ให้ทำการ clone , seed ข้อมูล และ run ตัว back-end ของเราจาก
* https://github.com/stroke-suandok/stroke-backend.git\
 จากนั้นจึงเริ่มทำขั้นตอนต่อไปนี้

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Works need to be done for operation.

* จัดการหน้า graph ให้การ track node ต้องจัดการกับลำดับ node
* เมื่อสถานะ node ทุก node ที่ต้องการเป็น success ให้ return ไปยังหน้า card และเปลี่ยนสถานะของ card
* จัดการ roles ของ user ที่มีมากเกินความจำเป็น
* ทำให้สามารถ add node แยกออกมาจาก blueprint ได้เพื่อความยืดหยุ่นและการปรับใช้ในสถานการณ์จริง

<p align="right">(<a href="#readme-top">back to top</a>)</p>






<!-- CONTACT -->
## Member

เธียร สุวรรณกุล 620610176 \
สุวิชาดา ปงกันมูล 630610657 \
ภูรินท์ ประสิทธิ์ 630610753 \
พีระ อรุณรัตน์ 630612184 \
ชลนันต์ ทองไทย 640610625 \
ปิยพัชร ขาวแสง 640610651 

<p align="right">(<a href="#readme-top">back to top</a>)</p>





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Vite.js]: https://img.shields.io/badge/vite.js-563D7C?style=for-the-badge&logo=vitedotjs&logoColor=white
[Vite-url]: https://vitejs.dev/
[Mantine]:https://img.shields.io/badge/mantine-4287f5?style=for-the-badge&logo=vitedotjs&logoColor=white
[Mantine-url]: https://mantine.dev/
[Reactflow]:https://img.shields.io/badge/reactflow-ea3373?style=for-the-badge&logo=vitedotjs&logoColor=white
[Reactflow-url]: https://reactflow.dev/

