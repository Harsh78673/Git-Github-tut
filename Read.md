# Git & Github Tutorial

### git commands in order and their meanings.

First aap [github.com](https://github.com) pe jake ek new repositary bnao then jo project ko git pe push krna chahte hai uska folder apne pc or laptop me create krke ye commands run kre vscod ki terminal me.

- First command is `git init` isko terminal me run krne pe apke folder me git ki ek repository create ho jayegi. 

- Second command is `git add .` git add all means ki hum humare is folder ki sari files ko aur folders ko ready krna chahte hai github pe dalne k liye. Ki mai is folder ki sari files ko github pr upload krna chahta hu. Isme . dot ka matlab all hai. 

    - Pehle apki index.html and sari files ke right side pe U likha aa rha tha kyuki vo git pe upload hi thi and ab A hai jiska mtlab hai ki index added ki file git me added hai.

- Third command is `git commit -m"message of what changes has been made in this project"` iska matlab hai ki mai is folder ki apne saare changes ko save krna chahta hu and '-m'means message ji ki "" doublequotes me likha jat ahai ki hume kya change kiya hai project me.

    - Ab agar apne git me pehle nhi login kiya hai to ye apse aapki id mange ga. Iske liye First command
    jo run krni hai vo hai: `git config --global user.email "your@emain.com"` Second command hai: `git config --global user.name "Your Name"`. First command me apko apna github ki idvala email dena hai and Second command me apko apna username dena hai. Iske baad ek baar fir se commit kro taki sab kuch commit ho jaye.

- Fourth command :  `git branch -M main` means ik new branch bnao main ki and uske andar sara kuch daal do

- Fifth command : `git remote add origin https://github.com/Harsh78673/Git-Github-tut.git` ye command important hai ye apko sirf iss ek project me hi milegi and ye vali command har ek project ki alag hogi jo git deta hai. 

- Sixth command hai: `git push -u origin main` means jo maine main branch bnai thi mai usme code ke saare changes push krna chahta hu.

> ***Important info:-*** Kuch bhi edit krne ke baad `git add .` git add all run kro then commit kro `git commit -m"changes here"` fir iske baad `git push -u origin main` command run kro ye command run krni jruri hai iske run hone ke baad hi sara kuch github pe push hoga.


There are two things push and pull in github. ***git pull*** ka matlab hai ki mai main branch se sara code apne laptop me lena chahta hu.And ***git push*** ka matlab hai ki maine project me jo kaam kiya hi mai usko github pe main branch me bhejna chahta hu. 

---
> Now hum font ko light bnayenge normal font 'ttf' vala hota hai joki heavy hot ahai hum usko 'woff2' me convert krenge jo ki vary light hota hai. To do this humko google pe search krna hai ttf to woff2 fir waha pe apko apna ttf wala font upload krna hai and fir waha se woff2 wala download krna hai convert hone k baad. 
>
> Iske baad apko image ko bhi jpg se webp me convert krna hai to make it light. Image ko convert krne k liye bhi same site pe hi jana hai jaha se humne font convert kiya tha site ka link ye hai: **[cloudconverter.com](https://cloudconvert.com/)**.

#### Ab sara kuch compelete ho gaya hai jab aap github ko reload kro ge to apko is project ka sara code waha pe mil jayengi.

# Ab hum iss project ko github se host karenge.

 Isme hume ek baat ka dhyaan rkhan hai ki hmari main html file ka name index.html hi hona chahiye isko yaha pe host krne k liye.

- Ab apko is project ke github ki settings me jana hai. Fir pages pe jana hai. Ab apko pages k andar branch me none ko main krkr save kr dena hai. Iske baad page reload hoga and then humko kuch der wait krna hoga fir 10 to 15 minutes ke baad page upload krna hoga fir hmara ye project live ho jayega.


