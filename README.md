# information-security-systems-assignment-33-solved
**TO GET THIS SOLUTION VISIT:** [Information-Security-Systems Assignment 33 Solved](https://www.ankitcodinghub.com/product/information-security-systems-assignment-33-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98703&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Information-Security-Systems Assignment 33 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
In this assignment you are going to develop an asymmetric encryption tool in C, from scratch. The purpose of this assignment, now that you are familiar with implementing simple ciphers as well as using real encryption toolkits, is to provide you the opportunity to get familiar with the internals of a popular encryption scheme, namely RSA. The tool will provide RSA key-pair generation, encryption and decryption.

More specifically, you are going to use the basic theory behind RSA and asymmetric encryption in order to develop the basics that compose a simple RSA toolkit, such as prime number generation and so on.

Task A

[Key Derivation Function (KDF)]

In this task you have to implement an RSA key-pair generation algorithm. In order to do so, you will first need to study RSA’s internals: ​https://en.wikipedia.org/wiki/RSA_(cryptosystem) . Moreover, you will need to develop a function that implements the Sieve Of Eratosthenes: https://en.wikipedia.org/wiki/Sieve_of_Eratosthenes . This material serves just as a reference point. You can also utilize any other source you wish. The key generation process will be the following:

<ol>
<li>Generate a pool of primes using the Sieve Of Eratosthenes. For your convenience, the sieve’s limit is defined in the provided file, rsa.h.</li>
<li>Pick two random primes from the pool. Lets name them ​p​ and ​q​.</li>
<li>Compute ​n​ where ​n = p * q​.</li>
<li>Calculate ​fi(n) where ​fi(n) = (p – 1) * (q – 1)​. This is Euler’s totient function, as described
in the original RSA paper “​A Method for Obtaining Digital Signatures and Public-Key Cryptosystems”​ . You may find out that other implementations use different totient functions. However, for this implementation, we are going to use Euler’s.
</li>
<li>Choose a prime ​e where ​(e % fi(n) != 0) AND (gcd(e, fi(n)) == 1) where gcd() is the Greatest Common Denominator.</li>
<li>Choose​d​where​d​isthe​modularinverseof(e,fi(n)).​</li>
<li>The public key consists of ​n ​and ​d​, in this order.​</li>
<li>The private key consists of ​n ​and ​e​, in this order.</li>
</ol>
Hints​:

<ul>
<li>● &nbsp;Use size_t when declaring the variables described above</li>
<li>● &nbsp;The key file should just contain the two numbers, (e.g. ​n and ​d​) so it just contains two
size_t variables
</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Task B

[Data Encryption]

Develop a function that provides RSA encryption functionality, using the keys generated in the previous step. This function reads the data of an input file and encrypts them using one of the generated keys. Then, it stores the ciphertext to an output file. For each character (1-byte) of the plaintext, the tool generates an 8-byte ciphertext (size_t on 64-bit machines). For example, if the plaintext is “hello” then the 5 bytes (5 chars) of the plaintext will produce 40-bytes (5 * sizeof(size_t)) of ciphertext.

Task C

[Data Decryption]

Implement a function that reads a ciphertext from an input file and performs RSA decryption using the appropriate one of the two keys, depending on which one was used for the ciphertext encryption. The keys will be generated using the KDF described in Task A. When the decryption is over, the function stores the plaintext in an appropriate output file.

IMPORTANT: In order to successfully decrypt the data, you have to use the appropriate key. If the ciphertext is encrypted using the public key, you have to use the private key in order to decrypt the data and vice versa. Also, every 8-bytes of the ciphertext produce a 1-byte plaintext. For example, a 40-byte ciphertext will produce a 5-byte plaintext.

Task D

[Using the tool]

Once you have implemented all the above functionality for your tool, use it to do the following operations, on the txt files provided for validation and testing purposes:

<ol>
<li>Encrypt the file “hpy414_encryptme_pub.txt” using the hpy414_public.key. Name the output as TUC&lt;AM&gt;_encrypted_pub.txt”</li>
<li>Decrypt the file “hpy414_decryptme_pub.txt” using the hpy414_public.key. Name the output as TUC&lt;AM&gt;_decrypted_pub.txt.</li>
<li>Encrypt the file “hpy414_encryptme_priv.txt” using the hpy414_private.key. Name the output as TUC&lt;AM&gt;_encrypted_priv.txt.</li>
<li>Decrypt the file “hpy414_decryptme_priv.txt” using the hpy414_priv.key. Name the output as TUC&lt;AM&gt;_decrypted_priv.txt.</li>
</ol>
Hints​:

● Remember that the key files contain just two size_t values. The first 8 bytes represent ​n

while the next 8 bytes represent ​e ​or ​d,​ depending on the key.

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
Tool Specifications

In order to assist you in the development of this tool, we provide a basic skeleton of the tool. We also provide some helper functions, used to print the plaintext as a string and the bytes of the ciphertext and keys in a human readable form. The tool will receive the required arguments from the command line upon execution as such:

</div>
</div>
<div class="layoutArea">
<div class="column">
Options:

</div>
</div>
<div class="layoutArea">
<div class="column">
-i -o -k -g -d -e -h

</div>
<div class="column">
path path path

</div>
<div class="column">
Path to input file

Path to output file

Path to key file

Perform RSA key-pair generation) Decrypt input and store results to output Encrypt input and store results to output This help message

</div>
</div>
<div class="layoutArea">
<div class="column">
The arguments “i”, “o” and “k” are always required when using “e” or “d” Using -i and a path the user specifies the path to the input file.

Using -o and a path the user specifies the path to the output file.

Using -k and a path the user specifies the path to the key file.

Using -g the tool generates a public and a private key and stores them to the public.key and private.key files respectively.

Using -d the user specifies that the tool should read the ciphertext from the input file, decrypt it and then store the plaintext to the output file.

Using -e the user specifies that the tool should read the plaintext from the input file, encrypt it and store the ciphertext to the output file.

Example​: ./assign_3 -g

The tool will generate a public and a private key and store them in the files public.key and private.key respectively.

Example​:

./assign_3 -i plaintext.txt -o ciphertext.txt -k public.key -e

The tool will retrieve the public key from the file public.key and use it to encrypt the data found in “plaintext.txt” and then store the ciphertext to “ciphertext.txt”

IMPORTANT

Even if you chose to redesign your tool from scratch, and not use the provided skeleton, you have to support the command line options described above.

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
Important notes

<ol>
<li>You need to submit all the source code of your tool, a README file, a Makefile, and all the files you used or generated in Task D. The README file should briefly describe your tool. You should place all these files in a folder named &lt;AM&gt;_assign3 and then compress it as a .zip file. For example, if your login is 2020123456 the folder should be named 2020123456_assign3 you should commit 2020123456_assign3.zip.</li>
<li>Study carefully the operation of RSA and the Sieve Of Eratosthenes.</li>
<li>Do ​not​ copy-paste code from online examples, we will know 😉</li>
<li>The tool’s skeleton provided with this assignment is just an example. Feel free to define
your own functions or change the signatures of the given functions. You can even re-design it from scratch. However, the switches defined above have to be kept the same.
</li>
<li>The ciphertext and the keys are just bytes. That means that they do ​not terminate with \0. Don’t try to print them as strings, use the provided functions, if needed.</li>
<li>Use the tab “Συζήτηση” in courses for questions.</li>
<li>Questions will be answered on Tuesday and Friday.</li>
</ol>
</div>
</div>
</div>
</div>
