# Sectoin 8

## **64**

### **[slides for this section](https://www.canva.com/en_gb/login/?redirect=%2Fdesign%2FDAEVUT6HslA%2FtbdbyITzamUidWfk-HcSug%2Fview%3Futm_content%3DDAEVUT6HslA%26utm_campaign%3Ddesignshare%26utm_medium%3Dlink%26utm_source%3Dpublishsharelink)**

## **65-66**

### **[git diff docs](https://git-scm.com/docs/git-diff)**

### **git diff**
>shfaq qka osht heq edhe shtu, only unstaged
>
>→ rreshti është shtuar në file
>
>→ rreshti është hequr nga file
>
>@@ ... @@ → tregon range/rreshtat në file ku ndodhin ndryshimet
>
>diff --git a/file b/file → tregon emrin e file-it që po ndryshon
>
>index <hash>..<hash> <mode> → versionet e file-it që po krahasohen

## **68**

### **git diff HEAD**
>Tregon të gjitha ndryshimet që i ke bërë në kod ndaj HEAD (branch-i aktual
>
>pra commit-i i fundit në branch ku je

### **git diff HEAD fileName**
>per file caktume

### **git diff --staged**
>Tregon ndryshimet që i ke bërë git add (pra që janë në staging area)
>
> krahasuar me HEAD (commit-i i fundit në branch-in aktual).


### **git diff --staged fileNme**
>per file caktume


### **git diff branch1..branch2**
>diferencat mes dy branch-ave
>
>bone edhe qeshtu
>mujna mi mar commitat te git log --online edhe atu mi kqyr diferencen mos komitav
>
>git diff 45678..78945
>git diff branch1 branch2

## **74**

### **[git exercise instructionsc](https://plum-poppy-0ea.notion.site/Git-Diff-Exercise-f7829bd2783940cea14239022a6c37a9)**

### **HEAD~1**
>HEAD = the latest commit in your current branch.
>
>HEAD~1 = the commit before HEAD (one commit back).
>
> HEAD~2 = two commits back, etc.
