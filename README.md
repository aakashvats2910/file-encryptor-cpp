# file-encryptor-cpp

Info: A simple yet powerful txt file encryptor/decryptor in C++ programming language.

# How it works

1. Run the executable or run in debug mode from VS Studio.
<img src="https://i.imgur.com/8gFLd9K.png"/>
<br/>

2. Choose one of the following option by typing the number infront of them.
<br/>
3. Now if you choose option 1 or 2 you will be asked to provide file path/location (this is the path of the file you want to encrypt/decrypt)
<br/>
4. Now you will be aksed to enter you secret number key. <i> For encryption you will be entering it for the first time(dont forget it) and for decryption you should enter the key provided at the time of encryption</i>
<br/>
5. You output file will be saved in the same directory of executable.
<img src="https://i.imgur.com/6vglbs5.png"/>

# Theory behind working

The algorithm part of this application is basic binary operations.

<ul>

<li>If we take two number, say x and y and do ^ (xor) operation on them we will get a number z</li>

<li>now from here we can observer that if we do x ^ z we get y, and if we do y ^ z we get x</li>

</ul>

```cpp
x = 50
y = 30
z = x ^ y = 44

also,

50 ^ 44 = 30
30 ^ 44 = 50
```

