# Section 11

## **93)**

### **[Slides For This Section](https://www.canva.com/design/DAEPtdekgz0/FLOqNt4RpDq1aWo1W-Df3A/view?utm_content=DAEPtdekgz0&utm_campaign=designshare&utm_medium=link&utm_source=editor)**

## **94)**

### **[GitHub Home Page](https://github.com/)**

### **Git**
>Një tool (software) për version control
>
>Punon lokalisht në PC
>
>Ruajnë historinë e kodit (commits)
>
>Lejon branch, merge, diff, etj.


### **GitHub**
>Një platformë online që përdor Git
>
>Ruajnë repos në cloud
>
>Lejon sharing & collaboration
>
>Ka features si pull requests, issues, etj.


## **95)**

### **[Why should use github](https://github.com/facebook/react)**


## **96)**

### **[git clone doc](https://git-scm.com/docs/git-clone)**


### **[2048 github repo](https://github.com/gabrielecirulli/2048)**


### **[hiring-without-whiteboards](https://github.com/poteto/hiring-without-whiteboards)**

### **git clone gitHubRepoLink**
>e bon clone repon n local
>
>KUJDES
>
>MOS E SHTI N REPO QE JE


## **97)**

### **[gitlab sample repo](https://gitlab.com/gitlab-tests/sample-project)**

## **98)**

### **[generating and adding SSH Keyes Guide](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)**


### **git config user.email**
>e bon clone repon n local


### **per me save key**
>copy

### **[new ssh](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)**


### **SSH**
>```
>ssh-keygen -t ed25519 -C "rrezbuzuku@gmail.com"
>```


>```
>eval "$(ssh-agent -s)"
>```

>```
>ssh-add ~/.ssh/id_ed25519
>```

>```
>cat ~/.ssh/id_ed25519.pub
>```

tani hin github -> setting -> SSH and GPG keys -> add new SSH key -> shkruje qata qe ta ka qit output prej cat ~/.ssh/id_ed25519.pub

## **99-100**


### **git remote -v**
>per me kqyr a ekziston naj remotes per repo
>
>veq i liston remote , nese ska sqet sen


### **git remote add <name> <url>**
>per me kqyr a ekziston naj remotes per repo

### **git remote rename <old> <new>**
>me ja ndrru emrin


### **git remote remove <name>**
>me fshi


## **101)**

### **[git pusb docss](https://git-scm.com/docs/git-push)**

### **git push <remote> <branch>**
>per me push n repo
>
>git push origin master
>
>kto bohen update veq n banch specifik jo te kejt branch-at

### **git push <remote> <locakBranch>:<remoteBranch>**
>git push origin cats:Master
>
>means: get senet prej our local Branch edhe boj push te remote Branch


### **git push -u**
>Upstream = branch-i remote me të cilin lidhet branch-i yt lokal
>
>Lokal: main (në PC)
>
>Remote: origin/main (në GitHub)
>
>Kur i lidh këto → krijohet upstream relationship
>
>pra nuk kena nevoj tash me bo git push origin bla bla po veq :
>```
>git push
>```
