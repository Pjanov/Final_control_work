### Задание 5. 

Выложить историю команд в терминале ubuntu

### Реализация

```
pjanov@Linux:~$ su
Пароль:
root@Linux:/home/pjanov# dpkg -i Downloads/python3-renderpm_3.6.8-1ubuntu0.1_amd64.deb
(Reading database ... 248945 files and directories currently installed.)
Preparing to unpack .../python3-renderpm_3.6.8-1ubuntu0.1_amd64.deb ...
Unpacking python3-renderpm:amd64 (3.6.8-1ubuntu0.1) over (3.6.8-1) ...
dpkg: dependency problems prevent configuration of python3-renderpm:amd64:
python3-renderpm:amd64 depends on libc6 (>= 2.14); however:
Package libc6:amd64 is not installed.

dpkg: error processing package python3-renderpm:amd64 (--install):
dependency problems - leaving unconfigured
Errors were encountered while processing:
python3-renderpm:amd64
root@Linux:/home/pjanov# history
1  sudo /etc
2  /etc
3  sudo apt update
4  sudo apt install mc
5  sudo apt install openssh-server
6  cd /etc
7  sudo nano sudoers
8  exit
9  cd /etc
10  sudo nano sudoers
11  exit
12  for pkg in docker.io docker-doc docker-compose podman-docker containerd runc; do sudo apt-get remove $pkg; done
13  sudo apt-get update
14  sudo install -m 0755 -d /etc/apt/keyrings
15  echo   "deb [arch="$(dpkg --print-architecture)" signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu \
16    "$(. /etc/os-release && echo "$VERSION_CODENAME")" stable" |   sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
17  cat /etc/apt/sources.list.d/docker.list > /dev/null
18  echo   "deb [arch="$(dpkg --print-architecture)" signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu \
19    "$(. /etc/os-release && echo "$VERSION_CODENAME")" stable" |   sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
20  cat /etc/apt/sources.list.d/docker.list
21  sudo apt-get update
22  sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
23  sudo docker run hello-world
24  sudo service docker start
25  docker stop
26  for pkg in docker.io docker-doc docker-compose podman-docker containerd runc; do sudo apt-get remove $pkg; done
27  sudo apt update
28  sudo apt-get install ca-certificates curl gnuhg
29  for pkg in docker.io docker-doc docker-compose podman-docker containerd runc; do sudo apt-get remove $pkg; done
30  sudo apt-get install language-pack-ru
31  apt install cpu-checker
32  kvm-ok
33  sudo apt-get update
34  sudo apt-get install apt-transport-https ca-certificates curl software-properties-common
35  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
36  sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
37  sudo apt-get update
38  sudo apt-get install docker-ce
39  sudo apt -y install docker-ce docker-ce-cli containerd.io
40  sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
41  sudo usermod -aG docker pjanov
42  sudo reboot
43  sudo docker run hello-world
44  for pkg in docker.io docker-doc docker-compose podman-docker containerd runc; do sudo apt-get remove $pkg; done
45  sudo apt-get update
46  sudo apt-get install ca-certificates curl gnupg
47  sudo install -m 0755 -d /etc/apt/keyrings
48  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg
49  sudo chmod a+r /etc/apt/keyrings/docker.gpg
50  echo   "deb [arch="$(dpkg --print-architecture)" signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu \
51    "$(. /etc/os-release && echo "$VERSION_CODENAME")" stable" |   sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
52  sudo apt-get update
53  sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
54  sudo docker run hello-world
55  docker ps
56  sudo apt install cowsay
57  /usr/games/cowsay "GeekBrains"
58  touch Dockerfile
59  nano Dockerfile
60  cat Dockerfile
61  docker build -t cowsaytest .
62  docker run -it cowsaytest bash
63  docker run cowsaytest cowsay "GeekBrains"
64  docker images
65  nano Dockerfile
66  cat Dockerfile
67  docker build -t cowsaytest .
68  docker images
69  nano Dockerfile
70  docker images
71  docker build -t cowsaytest .
72  docker images
73  docker run cowsaytest cowsay "GeekBrains"
74  vi Dockerfile
75  nano Dockerfile
76  docker build -t cowsaytest .
77  docker images
78  nano Dockerfile
79  docker build -t cowsaytest .
80  nano Dockerfile
81  docker build -t cowsaytest .
82  docker images
83  docker ps
84  docker rm 9c7a54a9a43c
85  docker rm hello-world
86  docker ps
87  docker rmi 9c7a54a9a43c
88  docker rmi hello-world
89  exit
90  nano Dockerfile
91  mkdir sem_4
92  cd sem_4/
93  nano Dockerfile
94  docker images
95  docker build -t cowsay .
96  exit
97  docker rmi
98  docker images
99  docker rm -f $(docker ps -a -q)
100  docker images
101  docker container prune -f
102  docker rmi -f $(docker images -a -q)
103  docker images
104  cd sem_4/
105  nano Dockerfile
106  docker build -t cowsay .
107  doscker images
108  docker images
109  nano Dockerfile
110  docker run cowsay
111  docker images
112  docker rmi b993a4e3bdfb --force
113  docker images
114  ~
115  #
116  exit
117  nano HelloWorld.java
118  rm -r app
119  ls
120  mkdir hw_4
121  cd hw_4/
122  nano Dockerfile
123  docker build -t my-java-app . # Сохранить файлы и запустить образ
124  docker images
125  mkdir /usr/src/app
126  cd /usr/src/app
127  .
128  cd .
129  cd ..
130  ls
131  exit
132  rm -r HelloWorld.java
133  cd shered/
134  ls
135  cd app/
136  ls
137  cd src/
138  ls
139  cd main/
140  ls
141  cd java/
142  ls
143  cd org/
144  ls
145  cd example/
146  ls
147  cd HelloWorld.java
148  exit
149  ls
150  cd hw_4/
151  ls
152  rm -r app/
153  ls
154  rm -r sem_4/
155  rm -r hw_4/
156  rm -r Dockerfile
157  clear
158  mkdir hw_4
159  cd hw_4/
160  nano Dockerfile
161  docker build -t my-java-app .
162  docker build -t my-java-app .
163  nano Dockerfile
164  docker build -t my-java-app .
165  nano Dockerfile
166  docker build -t my-java-app .
167  nano Dockerfile
168  docker build -t my-java-app .
169  cp /home/pjanov/shered/app /home/pjanov/hw_4/
170  cp -r /home/pjanov/shered/app /home/pjanov/hw_4/
171  cp -r /home/pjanov/shered/app/src/main/java/org/example/HelloWorld.java /home/pjanov/hw_4/
172  docker build -t my-java-app .
173  nano Dockerfile
174  docker build -t my-java-app .
175  nano Dockerfile
176  docker build -t my-java-app .
177  docker run -it my-java-app
178  docker images
179  docker rmi 111e5f9655be --force
180  docker images
181  nano Dockerfile
182  echo "public class HelloWorld {
183      public static void main(String[] args) {
184          System.out.println("Hello world!");
185      }
186  }" > HelloWorld.java
187  nano Dockerfile
188  docker build -t my-java-app .
189  docker run -it my-java-app
190  nano Dockerfile
191  docker build -t my-java-app .
192  nano Dockerfile
193  nano HelloWorld.java
194  docker build -t my-java-app .
195  docker run -it my-java-app
196  nano Dockerfile
197  cd hw_4/
198  ls
199  nano H
200  nano HelloWorld.java
201  ps -a
202  docker images
203  exit
204  ps -a
205  docker rm $(docker ps -a -q)
206  ps -a
207  docker images
208  docker rmi 34ba6cf7619b f87846dacdf4 --force
209  docker images
210  sudo chown -R superuser:pjanov hw_4
211  sudo chown -R pjanov:pjanov hw_4
212  sudo chown -R pjanov:pjanov pjanov
213  cd hw_4/
214  mkdir Task_2
215  cd Task_2
216  nano Dockerfile
217  docker build -t testconteiner .
218  nano Dockerfile
219  docker build -t testconteiner .
220  nano Dockerfile
221  docker build -t testconteiner .
222  docker run -d -p 8081:80 testconteiner
223  curl localhost:8081
224  exit
225  ls
226  cd shered/
227  ls
228  cd hw_5/
229  ls
230  cd web/
231  ls
232  cd app/
233  docker-compose up -d
234  cd ..
235  ls
236  rm -r hw_5
237  ls
238  clear
239  docker images
240  docker rmi cdff5d140a6a 0c88fbae765e cc1ef98c263b 039bd724508b --force
241  docker images]
242  docker images
243  docker ps
244  clear
245  mkdir hw_5
246  cd hw_5
247  nano docker-compose.yaml
248  mkdir web
249  cd web/
250  nano Dockerfile
251  cd ..
252  docker-compose up -d
253  docker-compose up --build
254  docker-compose up -d
255  docker images
256  docker ps
257  echo "собаки, кошки, хомяки" > "Домашние животные"
258  echo "лошади, верблюды, ослы" > "Вьючные животные"
259  cat "Домашние животные" "Вьючные животные" > "Друзья человека"
260  cat "Друзья человека"
261  history
262  cat "Домашние животные" "Вьючные животные" > "Домашние и Вьючные животные"
263  cat "Домашние и Вьючные животные"
264  mv "Домашние и Вьючные животные" "Друзья человека"
265  mkdir Животные
266  mv Домашние\ животные Вьючные\ животные Животные
267  mv Друзья\ человека Животные
268  sudo apt-key adv --keyserver pgp.mit.edu --recv-keys 5072E1F5
269  sudo sh -c 'echo "deb http://repo.mysql.com/apt/debian/ stretch mysql-5.7" >> /etc/apt/sources.list.d/mysql.list'
270  apt-get update
271  apt-get install mysql-server-5.7
272  dpkg -i package.deb
273  ls
274  cd Животные/
275  ../
276  ..
277  ls
278  cd../
279  cd..
280  cd ../
281  mkdir new_dir_dpkb
282  ls
283  cd new_dir_dpkb/
284  touch package.ded
285  dpkg -i package.ded
286  apt-get install -f
287  dpkg -i package.ded
288  cd ..
289  ls
290  dpkg -i Downloads/app grid_0.298_all.deb
291  ls
292  cd shered/
293  ls
294  cd ..
295  ls
296  cd sh
297  cd shered/
298  ls
299  cd ..
300  cd new_dir_dpkb/
301  apt update
302  apt search gimp
303  apt install gimp
304  ls
305  cd ..
306  ls
307  cd Downloads/
308  sudo dpkg -i vivaldi-stable_3.8.2259.42-1_amd64.deb
309  sudo dpkg -i vivaldi-stable_6.1.3035.111-1_armhf.deb
310  cd ..
311  dpkg -i vivaldi-stable_6.1.3035.111-1_armhf.deb
312  dpkg -i Downloads/vivaldi-stable_6.1.3035.111-1_armhf.deb
313  ls
314  cd Dow
315  ls
316  cd Downloads/
317  ls
318  dpkg -i vivaldi-stable_6.1.3035.111-1_armhf.deb
319  cd ..
320  dpkg -i vivaldi-stable_6.1.3035.111-1_armhf.deb
321  dpkg -i Downloads/vivaldi-stable_6.1.3035.111-1_armhf.deb
322  dpkg -i Downloads/libc6_2.31-0ubuntu9.7_amd64.deb
323  apt-get install --download-only nombre-del-paquete
324  ls
325  cd ..
326  ls
327  cd ..
328  ls
329  cd /var/cache/apt/archives
330  ls
331  cp libreoffice-help-ru_1%3a7.3.7-0ubuntu0.22.04.3_all.deb
332  /Downloads
333  cd pjanov/
334  cd ..
335  ~
336  dpkg -i Downloads/python3-renderpm_3.6.8-1ubuntu0.1_amd64.deb
337  history
root@Linux:/home/pjanov# 
```