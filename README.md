<h1 align="center">Hi, I'm Stepan Kutaj</h1>
<h3 align="center">A passionate Linux and DevOps</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=stepankutaj&label=Profile%20views&color=0e75b6&style=flat" alt="stepankutaj" /> </p>

<p align="left"> <a href="https://twitter.com/clowicek" target="blank"><img src="https://img.shields.io/twitter/follow/clowicek?logo=twitter&style=for-the-badge" alt="clowicek" /></a> </p>

- 🔭 I’m currently working on [Ansible project](https://github.com/IAM-K8S/iamk8s-ansible)

- 📫 How to reach me **info@iam-k8s.cloud**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://twitter.com/clowicek" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="clowicek" height="30" width="40" /></a>
<a href="https://linkedin.com/in/stepankutaj" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="stepankutaj" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> </p>

<h2>Prerequisites</h2>
Install Ansible application - <a href="https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html" target="_blank">Ansible documentation</a>

<h2>Installation</h2>
<p>Working with this linux distribution:</p>
<b>Debian based</b>
<ul>
  <li>Debian 9/10/11/12  --- stretch/buster/bullseye/bookworm  </li>
  <li>Ubuntu 20.04/22.04 --- Focal Fossa/Jammy Jellyfish</li>
</ul>
<b>RedHat based</b>
<ul>
  <li>RedHat Enterprise Linux 7/8/9</li>
  <li>AlmaLinux 8/9</li>
  <li>CentOS 8/9</li>
</ul>
<pre>
 git clone https://github.com/IAM-K8S/iamk8s-ansible
 cd iamk8s-ansible/
</pre>
Open inventory files and add or modify linux host which will be updated.
<pre>vim inventory/inventory</pre>

for example:
<pre>
[all]
test.local.domain 
</pre>

Check file vars.yml in group_vars and update default settings.
<pre>
vim inventory/group_vars/all/vars.yml
</pre>
for example weather for New York:
<pre>
weather_city: NewYork
</pre>
You must remove spaces in city names.

<h2>Run Ansible</h2>
just type...
<pre>
cd iamk8s-ansible/
ansible-playbook playbook/base.yml
</pre>

motd
![image](https://github.com/IAM-K8S/iamk8s-ansible/assets/3997208/f476105e-03a5-40d4-8dc2-1e2187610345)

iptables
![image](https://github.com/IAM-K8S/iamk8s-ansible/assets/3997208/84379649-5a74-4591-a0e4-a848f0d534f4)

weather

