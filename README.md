# Documentation_session1
Describe all tasks we went through the session1

	I- What is version control ?

Version control, also known as source control, is the practice of tracking and managing
changes to software code.


	II- How to downloading and install Golang ?

*Download the file depending of you system here : https://go.dev/dl/

#For LINUX
a- Remove any previous Go installation by deleting the /usr/local/go folder (if it exists),
then extract the archive you just downloaded into /usr/local, creating a fresh Go tree in /usr/local/go:
$ rm -rf /usr/local/go && tar -C /usr/local -xzf go1.22.0.linux-amd64.tar.gz

(You may need to run the command as root or through sudo).

Do not untar the archive into an existing /usr/local/go tree. This is known to produce broken Go installations.

b- Add /usr/local/go/bin to the PATH environment variable.
You can do this by adding the following line to your $HOME/.profile or /etc/profile (for a system-wide installation):

export PATH=$PATH:/usr/local/go/bin

Note: Changes made to a profile file may not apply until the next time you log into your computer.
To apply the changes immediately, just run the shell commands directly or execute them from the profile using a command such as source $HOME/.profile.


#For Mac
Open the package file you downloaded and follow the prompts to install Go.
The package installs the Go distribution to /usr/local/go. The package should put the /usr/local/go/bin directory
in your PATH environment variable. You may need to restart any open Terminal sessions for the change to take effect.

#For Windows
Open the MSI file you downloaded and follow the prompts to install Go.
By default, the installer will install Go to Program Files or Program Files (x86). You can change the location as needed.
After installing, you will need to close and reopen any open command prompts so that changes to
the environment made by the installer are reflected at the command prompt.


Verify that you've installed Go by opening a command prompt and typing the following command:
$ go version

Confirm that the command prints the installed version of Go.


	III- What is Golang?
Go, also called Golang or Go language, is an Open Source programming language that Google developed.
Software developers use Go in an array of operating systems and frameworks to develop web applications,
cloud and networking services, and other types of software.


	IV- Why choose Golang?
The advantages of Golang over others. Go is loved by the community for a number of reasons: it appears to be faster than most other languages,
has powerful error-handling patterns, and can support concurrency. All these make the language perfect for large-scale projects.
Let's learn a bit more about Golang's advantages ...

	V- Where to use Golang ?
Go was originally built for programs related to networking and infrastructure.
It was intended to replace popular high-performance server-side languages like Java and C++.
Today, Go is used for a variety of applications like cloud and server side applications, DevOps, command line tools and much more.
