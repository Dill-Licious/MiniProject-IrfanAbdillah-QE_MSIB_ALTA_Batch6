# Mini Project Quality Engineer MSIB Alterra Academy Batch 6

## About Project
Mini project ini disusun untuk menjalankan automation testing guna menguji API, website, dan mobile. Proyek ini dikembangkan oleh Muhamad Irfan Abdillah dari Institut Pertanian Bogor, MSIB Batch 6 Quality Engineering (QE) di Alterra Academy. Sistem yang diuji meliputi:  
- API: [Alta Shop API Documentation](https://documenter.getpostman.com/view/5781191/2s8YmULKUi#3b1e285f-26ce-4d18-a08e-547acfec5650)
- Website: https://mini-book-store-fe.vercel.app/
- Aplikasi: [Shopping List App](https://drive.google.com/file/d/1G7RYvlngeWdm-3kSR-Qx4paSNobwyEYp/view)



## Test Case Document
Berikut merupakan link test case dan test result:
- API: [API Testing Test Cases](https://app.qase.io/public/report/ba4a2be57756a6f5de2d4e199528c7f85852a18f)
- Web: [Website Testing Test Cases](https://app.qase.io/public/report/899e9b64d0e3be09cf169b07f4f2db9fb8ac5ac3)
- Mobile: [Mobile Testing Test Cases](https://app.qase.io/public/report/11439501b82266791a86a3ffe04f863d464b92df)

## Implementasi CI/CD
Implementasi CI/CD pada API Test: https://github.com/Dill-Licious/CI-Implementation-APITesting-MiniProject

## Tech Stacks
Berikut merupakan tools yang digunakan untuk melakukan pengujian dalam berbagai platform:
- API Testing: Postman, Rest Assured BDD
- Website Testing: Chrome Webdriver, Serenity BDD
- Mobile Testing: Appium Inspector, Appium Server, Cucumber.js
- System Version Control: Git, Github
- Test Case Management Tools: Qase.io

## Test Results
Berikut merupakan report dari hasil pengujian:
- API Testing: [PDF API Testing Report](Testing-Report/API%20Testing%20Report.pdf)
- Mobile Testing: [PDF Mobile Testing Report](Testing-Report/Mobile%20Testing%20Report.pdf)
- Website Testing: [PDF Website Testing Report](Testing-Report/Website%20Testing%20Report.pdf)

## Setup 
1. Clone this repository
2. Pastikan sudah memiliki Java, Maven, server appium
3. Set up .env file pada mobile, sambungkan dengan real device / virtual device
4. Cara menjalankan API test dan web test:
```
mvn clean verify
```
5. Cara menjalankan mobile test:
```
npm test
```


