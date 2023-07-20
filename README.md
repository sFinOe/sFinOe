<h1 align="center">Hi 👋, I'm Zakaria Kasmi</h1>
<h3 align="center">A Full Stack, Mobile Dev</h3>



```cpp
#include <about_me>

using namespace std

int main() {
    std::cout << "Launching New HTTP Connection!!!" << std::endl;

    int serverSocket = socket(AF_INET, SOCK_STREAM, 0);
    if (serverSocket < 0)
        _error(errno);

    int optval = 1;
    if (setsockopt(serverSocket, SOL_SOCKET, SO_REUSEADDR, &optval, sizeof(optval)) < 0)
        _error(errno);

    sockaddr_in serverAddress;
    serverAddress.sin_family = AF_INET;
    serverAddress.sin_addr.s_addr = inet_addr("127.0.0.1");
    serverAddress.sin_port = htons(3000);
    memset(&(serverAddress.sin_zero), '\0', 8);

    if (bind(serverSocket, reinterpret_cast<sockaddr*>(&serverAddress), sizeof(serverAddress)) < 0)
        _error(errno);

    if (listen(serverSocket, SOMAXCONN) < 0)
        _error(errno);

    std::cout << "Waiting For Connection!!!" << std::endl;

    sockaddr_in clientAddress;
    socklen_t clientAddressSize = sizeof(clientAddress);
    int clientSocket = accept(serverSocket, reinterpret_cast<sockaddr*>(&clientAddress), &clientAddressSize);
    if (clientSocket < 0)
        _error(errno);

    send(clientSocket, "Welcome To My Profile <3", 26, 0);

    std::cout << "Thanks For Visiting My Profile" << std::endl;

    close(clientSocket);
    close(serverSocket);

    return 0;
}
```





<p align="left"> <a href="https://twitter.com/zakie_kasmi" target="blank"><img src="https://img.shields.io/twitter/follow/zakie_kasmi?logo=twitter&style=for-the-badge" alt="zakie_kasmi" /></a> </p>

- 🔭 I’m currently working on [Mobile App With React-native](Coming-Soon)

- 🌱 I’m currently learning **Js, React-native, Node and Express Js and a lot more**

- 👯 I’m looking to collaborate on [Anything](Coming-Soon)

- 🤝 I’m looking for help with [C/C++, Js](zakkikasmi@gmail.com)

- 👨‍💻 All of my projects are available at [https://github.com/sFinOe](https://github.com/sFinOe)

- 📝 I regularly write articles on [https://disposkill.com](https://disposkill.com)

- 💬 Ask me about **C/C++, HTML/CSS, Js [React, native, Node], Docker**

- 📫 How to contact me **zakkikasmi@gmail.com**

- 📄 Know about my experiences [https://disposkill.com/about_me](https://disposkill.com/about_me)

- ⚡ Fun fact **I think i'm not funny**

### Blogs posts
<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://dev.to/sfinoe" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/devto.svg" alt="sfinoe" height="30" width="40" /></a>
<a href="https://twitter.com/zakie_kasmi" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="zakie_kasmi" height="30" width="40" /></a>
<a href="https://linkedin.com/in/sfinoe" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="sfinoe" height="30" width="40" /></a>
<a href="https://stackoverflow.com/users/sfinoe" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/stack-overflow.svg" alt="sfinoe" height="30" width="40" /></a>
<a href="https://fb.com/zakisblue" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="zakisblue" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>

![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)


<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=sfinoe&show_icons=true&locale=en&layout=compact" alt="sfinoe" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=sfinoe&show_icons=true&locale=en" alt="sfinoe" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=sfinoe&" alt="sfinoe" /></p>
