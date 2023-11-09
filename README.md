# new-project
devops week2 task


instruction text here ...
git init task2_v2
cd task2_v2
vi challenge.txt
cat challenge.txt| git hash-object -w --stdin > hash.txt
git cat-file -p d4aa0ec2a2fcca22b4d7c1c8a6989856377facf6 >> hash.txt
git update-index --add --cacheinfo 100644 d4aa0ec2a2fcca22b4d7c1c8a6989856377facf6 challenge.txt
git ls-files -s >> hash.txt

------
result:

cat hash.txt
d4aa0ec2a2fcca22b4d7c1c8a6989856377facf6
This is my Git challenge file
100644 d4aa0ec2a2fcca22b4d7c1c8a6989856377facf6 0       challenge.txt

