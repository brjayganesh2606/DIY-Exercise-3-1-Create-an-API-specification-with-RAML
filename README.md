DIY Exercise 3-1: Create an API specification with RAML

1)In Design Center , I have created new project named Demo_project .

It contains "/accounts" GET and POST method .

![image](https://user-images.githubusercontent.com/70746268/120195541-8deedd00-c23c-11eb-942d-e168b914fb80.png)

![image](https://user-images.githubusercontent.com/70746268/120195595-9c3cf900-c23c-11eb-9263-778e5317ae62.png)

2)Next ,I have created a new folder datatypes , In datatypes , I have created acc.raml which contains the response data type that contain the following fields: id, firstName, lastName, address, postal, country, miles, creationDate, and type. The creationDate field is of type datetime and miles is of type integer.

![image](https://user-images.githubusercontent.com/70746268/120196799-e672aa00-c23d-11eb-8289-7d88c855646f.png)

3)Next ,I have created a new folder examples , In examples , I have created ACCexample.raml which contains the GET data of the account holders .

![image](https://user-images.githubusercontent.com/70746268/120196879-fb4f3d80-c23d-11eb-99ae-e56bb3c13e78.png)

![image](https://user-images.githubusercontent.com/70746268/120197563-b677d680-c23e-11eb-823f-77fed55c4198.png)

4)Now ,in the same folder examples , I have created another file ACCNoID.raml which contains POST data .

![image](https://user-images.githubusercontent.com/70746268/120197688-deffd080-c23e-11eb-8eb1-f9a100d15a97.png)

5) In Documentation , sending GET request ,

![image](https://user-images.githubusercontent.com/70746268/120197797-09ea2480-c23f-11eb-9530-029450c7299c.png)

Getting 200 success code 

![image](https://user-images.githubusercontent.com/70746268/120197889-26865c80-c23f-11eb-8a20-f85fd607d894.png)

![image](https://user-images.githubusercontent.com/70746268/120197955-3736d280-c23f-11eb-9af3-c6263321affb.png)

![image](https://user-images.githubusercontent.com/70746268/120197986-4027a400-c23f-11eb-9d3c-b7d25dfb454f.png)

6)In Documentation , sending POST request ,

![image](https://user-images.githubusercontent.com/70746268/120198105-63525380-c23f-11eb-9f77-30b76e8176b7.png)

Getting 200 success code ,

![image](https://user-images.githubusercontent.com/70746268/120198193-79f8aa80-c23f-11eb-9d2a-207d296d73c2.png)

7)After publishing to exchange , I can see my new project in exchange Demo_project.

![image](https://user-images.githubusercontent.com/70746268/120200859-6bf85900-c242-11eb-8183-cc65a5a6a9f2.png)

8)In Demo_project ,

![image](https://user-images.githubusercontent.com/70746268/120201125-b37ee500-c242-11eb-904b-109901746b11.png)

9)In /account GET ,

![image](https://user-images.githubusercontent.com/70746268/120201210-d0b3b380-c242-11eb-9f85-ee52b2b35ccb.png)

Here too , we check , 200 success code with same answer ....

![image](https://user-images.githubusercontent.com/70746268/120201344-f6d95380-c242-11eb-87ce-122dec327cf9.png)

![image](https://user-images.githubusercontent.com/70746268/120201387-035dac00-c243-11eb-9c79-2174b71e109f.png)

10) In /account POST ,

![image](https://user-images.githubusercontent.com/70746268/120201520-2a1be280-c243-11eb-9c2f-154331f435a6.png)

Here too , we check , 200 success code with same answer ....

![image](https://user-images.githubusercontent.com/70746268/120201562-3869fe80-c243-11eb-8fcd-b794d9cb1994.png)

