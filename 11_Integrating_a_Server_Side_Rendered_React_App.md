# [Stephen Grider] Microservices with Node JS and React [ENG, 2020]

# 11. Integrating a Server-Side-Rendered React App

<br/>

### 01. Starting the React App

<br/>

### 02. Reminder on Server Side Rendering

<br/>

### 03. Basics of Next JS

    $ cd app
    $ mkdir client
    $ cd client
    $ npm init -y
    $ npm install --save react react-dom next

<br/>

    $ npm run dev

<br/>

### 04. Building a Next Image

<br/>

### 05. Running Next in Kubernetes

If chome will block page for security reasons, type: **thisisunsafe**

browser --> https://ticketing.dev/

<br/>

![Application](/img/pic-11-01.png?raw=true)

<br/>

### 06. Note on File Change Detection

<br/>

### 07. Adding Global CSS

    $ cd client
    $ npm install --save bootstrap

<br/>

![Application](/img/pic-11-02.png?raw=true)

<br/>

### 08. Adding a Sign Up Form

https://ticketing.dev/auth/signup

<br/>

### 09. Handling Email and Password Inputs

<br/>

### 10. Successful Account Signup

    $ cd clien
    $ npm install --save axios

<br/>

### 11. Handling Validation Errors

<br/>

![Application](/img/pic-11-03.png?raw=true)

<br/>

### 12. The useRequest Hook

<br/>

### 13. Using the useRequest Hook

<br/>

![Application](/img/pic-11-04.png?raw=true)

<br/>

### 14. An onSuccess Callback

<br/>

### 15. Overview on Server Side Rendering

<br/>

### 16. Fetching Data During SSR

<br/>

### 17. Why the Error

<br/>

![Application](/img/pic-11-05.png?raw=true)

<br/>

### 18. Two Possible Solutions

<br/>

![Application](/img/pic-11-06.png?raw=true)

<br/>

![Application](/img/pic-11-07.png?raw=true)

<br/>

### 19. Cross Namespace Service Communication

<br/>

![Application](/img/pic-11-08.png?raw=true)

<br/>

![Application](/img/pic-11-09.png?raw=true)

<br/>

### 20. When is GetInitialProps Called

<br/>

![Application](/img/pic-11-10.png?raw=true)

<br/>

![Application](/img/pic-11-11.png?raw=true)

<br/>

### 21. On the Server or the Browser

<br/>

### 22. Specifying the Host

<br/>

    http://SERVICENAME.NAMESPACE.svc.cluster.local

<br/>

    $ kubectl get ingress --all-namespaces
    NAMESPACE   NAME          CLASS    HOSTS           ADDRESS      PORTS   AGE
    default     ingress-svc   <none>   ticketing.dev   172.17.0.2   80      123m

<br/>

    // NOT WORKS for ME.
    http://ingress-svc.default.svc.cluster.local

<br/>

    $ kubectl exec -ti auth-deployment-5494fcdc44-hw75w -- nslookup 172.17.0.2
    nslookup: can't resolve '(null)': Name does not resolve

    Name:      172.17.0.2
    Address 1: 172.17.0.2 172-17-0-2.kubernetes.default.svc.cluster.local

<br/>

### 23. Passing Through the Cookies

<br/>

![Application](/img/pic-11-12.png?raw=true)

<br/>

![Application](/img/pic-11-13.png?raw=true)

<br/>

### 24. A Reusable API Client

<br/>

### 25. Content on the Landing Page

<br/>

### 26. The Sign In Form

<br/>

![Application](/img/pic-11-14.png?raw=true)

<br/>

### 27. A Reusable Header

<br/>

### 28. Moving GetInitialProps

<br/>

### 29. Issues with Custom App GetInitialProps

<br/>

### 30. Handling Multiple GetInitialProps

<br/>

### 31. Passing Props Through

<br/>

### 32. Building the Header

<br/>

### 33. Conditionally Showing Links

<br/>

### 34. Signing Out

<br/>

![Application](/img/pic-11-15.png?raw=true)

<br/>

---

<br/>

**Marley**

Any questions in english: <a href="https://jsdev.org/chat/">Telegram Chat</a>  
Любые вопросы на русском: <a href="https://jsdev.ru/chat/">Телеграм чат</a>
