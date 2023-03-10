# JavaScript-Api-practice-33

- [](#)

### internet

<details>
<summary>
  <h3>What is internet ? (Click Me)</h3>
</summary>
<br >

- The Internet is a global network of interconnected computers and devices that communicate with each other using a standardized set of protocols. It enables the exchange of information and data across vast distances, connecting people, organizations, and communities from all over the world.

```js

```

```js

```

</details>

<details>
<summary>
  <h3>What is IP addresses ? (Click Me)</h3>
</summary>
<br >

- IP addresses (Internet Protocol addresses) are unique numerical identifiers assigned to every device connected to a computer network that uses the Internet Protocol for communication. In other words, it is a numerical label assigned to each device, such as a computer or smartphone, that connects to the internet. IP addresses serve two primary functions: identifying the host or network interface and providing a location of the device in the network. IP addresses can be either static, which means they remain the same over time, or dynamic, which means they change periodically. IP addresses are essential for communication between devices on the internet, as they enable devices to send and receive data packets to the correct destination.

```js

```

```js

```

</details>

<details>
<summary>
  <h3>What is class ? (Click Me)</h3>
</summary>
<br >

- The Domain Name System (DNS) is the phonebook of the Internet
- human acces online throgh domain Name like rakib.com or espn.com
- web browser Interact throgh Internet protocol (IP) address
- DNS translates domain names to ip address so browsers can load internet resources

#### how to work dns

- DNS works by translating human-readable domain names, such as www.example.com, into machine-readable IP addresses, such as 192.0.2.1, which are used to identify devices on the internet. The process typically involves several steps:

- 1. When a user types a domain name into their web browser or other application, the application sends a request to a DNS resolver to obtain the corresponding IP address.

- 2. The DNS resolver first checks its local cache to see if it has a record of the IP address for the requested domain name. If the record is found, the resolver returns the IP address to the application.

- 3. If the record is not found in the local cache, the resolver sends a request to one or more DNS servers to find the IP address for the domain name.

- 4. The DNS servers work together in a hierarchical system to locate the IP address. If the requested domain name is a top-level domain (TLD), such as .com or .org, the resolver sends the request to a root DNS server, which responds with the IP addresses of the TLD DNS servers.

- 5. The resolver then sends the request to the appropriate TLD DNS server, which responds with the IP address of the DNS server responsible for the next level of the domain name hierarchy.

- 6. This process continues until the resolver receives the IP address of the DNS server responsible for the requested domain name.

- 7. The resolver then sends a request to the DNS server for the IP address of the domain name.

- 8. The DNS server responds with the IP address, and the resolver caches the record for future use.

- 9. Finally, the resolver returns the IP address to the application, which uses it to establish a connection with the server hosting the requested website.

- 10. This entire process is usually completed within a few milliseconds, allowing users to access websites and other resources on the internet quickly and easily.

```js

```

```js

```

</details>

<details>
<summary>
  <h3>What is HTTP?  ? (Click Me)</h3>
</summary>
<br >

- HTTP stands for Hypertext Transfer Protocol. It is an application protocol that governs how data is transmitted between clients and servers over the internet. Specifically, it is the protocol that enables communication between web browsers and web servers, allowing users to access websites and other online resources.

- HTTP operates by establishing a connection between a client, such as a web browser, and a server, which hosts the requested resource. The client sends an HTTP request to the server, specifying the resource it wants to access, such as a webpage or a file. The server then responds with an HTTP response, which includes the requested resource, along with other information, such as headers and metadata.

- HTTP is a stateless protocol, which means that each request/response transaction is independent of all others. This allows for efficient and scalable communication over the internet, as multiple clients can send requests to a server simultaneously without interfering with each other.

- HTTP is also extensible, allowing for the development of new features and functionality to be added over time. For example, HTTPS (HTTP Secure) is an extension of HTTP that adds encryption and authentication to enhance security.

- Overall, HTTP is a fundamental protocol of the internet, enabling users to access a vast array of online resources quickly and easily.

- Bangla :
- HTTP অর্থ হলো Hyper Text Transfer Protocol। ইন্টারনেটে টিসিপি/আইপি প্রটোকলের মাধ্যমে যে প্রটোকল ওয়েব সার্ভার ও ওয়েব ক্লায়েন্ট-এর মধ্যে ডেটা আদান-প্রদান করে তাকে এইচটিটিপি (HTTP) বলে। ক্লায়েন্ট বিভিন্ন ব্রাউজারের মাধ্যমে ওয়েবপেইজের জন্য সার্ভারকে অনুরোধ পাঠাতে থাকে। সার্ভার ক্লায়েন্টের অনুরোধে সাড়া দিয়ে ওয়েবপেইজকে ক্লায়েন্টের কাছে পাঠিয়ে দেয়। ক্লায়েন্ট বিভিন্ন ব্রাউজারের মাধ্যমে তা দেখতে পায়। আর যার মাধ্যমে ডেটা আদান-প্রদান হয় তা হলো এইচটিটিপি (HTTP)। সুতরাং এইচটিটিপি (HTTP) এর কাজ হচ্ছে– সার্ভারের সাথে ব্রাউজারের সংযোগ তৈরি করা, ব্রাউজারের যেকোনো অনুরোধ সার্ভারে পৌছে দেওয়া, ব্রাউজারের অনুরোধে সার্ভারের সাড়া মোতাবেক ওয়েবপেইজকে ব্রাউজারে নিয়ে আসা, ব্রাউজার এবং সার্ভারের সংযোগ বিচ্ছিন্ন করা।

```js

```

```js

```

</details>

<details>
<summary>
  <h3>What is API ? (Click Me)</h3>
</summary>
<br >

- In JavaScript, an API (Application Programming Interface) is a set of protocols, routines, and tools for building software applications. Specifically, an API allows developers to access the functionality of an existing system, such as a web service, database, or operating system, and use it to build new applications.

- APIs can be used in a variety of ways in JavaScript, such as:

- Web APIs: These are APIs built into web browsers that provide JavaScript developers with access to a variety of features and functionality, such as the Document Object Model (DOM), XMLHttpRequest (XHR), and Web Storage.

- T- hird-party APIs: These are APIs developed by third-party organizations that provide developers with access to their services, such as social media platforms, weather data, or financial data.

- Custom APIs: These are APIs developed by individual developers or organizations to provide access to their own systems or services.

- In JavaScript, developers typically interact with APIs by making requests using HTTP (or HTTPS) protocols and receiving responses in a standardized format, such as JSON (JavaScript Object Notation) or XML (Extensible Markup Language). This allows developers to easily integrate different systems and services into their applications, making them more powerful and versatile.

```js

```

```js

```

<details>
<summary>
  <h3>What is JSON ? (Click Me)</h3>
</summary>
<br >

- JSON (JavaScript Object Notation) is a lightweight data-interchange format that is used to transmit data between applications. It is based on a subset of the JavaScript programming language and is both human-readable and machine-readable. JSON is widely used for data serialization, which is the process of converting data objects into a format that can be easily transmitted over a network or stored in a file.

- JSON consists of two primary data structures: objects and arrays. An object is an unordered collection of name/value pairs, while an array is an ordered list of values. Both objects and arrays can be nested within each other to create complex data structures.

- Here is an example of a simple JSON object:

```js
{
  "name": "John Smith",
  "age": 32,
  "email": "john.smith@example.com"
}

```

- Bangla : JSON (JavaScript Object Notation) হল একটি লাইটওয়েট ডেটা-ইন্টারচেঞ্জ ফরম্যাট যা একটি জাভাস্ক্রিপ্ট অবজেক্টের মতো ডেটা স্ট্রাকচার বা ডেটা ফরম্যাট। এর উদ্দেশ্য অ্যাপ্লিকেশনগুলির মধ্যে ডেটা পাঠানোর জন্য একটি লাইটওয়েট ফরম্যাট উপস্থাপন করা। এটি জাভাস্ক্রিপ্টের একটি সাধারণ ডেটা ফরম্যাট হিসাবে ব্যবহৃত হয়।

JSON তিনটি প্রাথমিক ডেটা স্ট্রাকচার ব্যবহার করে: অবজেক্ট, অ্যারে, এবং স্ট্রিং। অবজেক্ট হল নেম/ভ্যালু পেয়ারের অসংখ্য সংগ্রহণ, অ্যারে হল মূলত নম্বরিত একটি সংগ্রহণ এবং স্ট্রিং হল টেক্সট স্ট্রিং বা বর্ণমালা। এই তিনটি স্ট্রাকচার একটি JSON ডেটা স্ট্রাকচার তৈরি করতে ব্যবহৃত হয়।

JSON ব্যবহার করা হয় ডেটা সিরিয়ালাইজেশনের জন্য, যা ডেটা অবজেক্টগুলি নেটওয়ার্কে পাঠান

example :

```js
const user = { id: 1, name: "Gorib Aamir", job: "Actor" };
//  javaScript object notation

const stringify = JSON.stringify(user);
console.log(user);
console.log(stringify);

/* { id: 1, name: 'Gorib Aamir', job: 'Actor' }
{"id":1,"name":"Gorib Aamir","job":"Actor"} */

const shop = {
  owner: "Alia",
  address: {
    street: "kochukhet voot er goli",
    city: "ranbir",
    country: "BD",
  },
  products: ["laptop", "mic", "monitor", "keyboard"],
  revenue: 45000,
  isOpen: true,
  isNew: false,
};

console.log(shop);
const shopJson = JSON.stringify(shop);
console.log(shopJson);
const shopObj = JSON.parse(shopJson);
console.log(shopObj);
```

</details>
