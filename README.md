# wordlist-s3-bucket
wordlist for s3 bucket enumeration....

Use this command to generate a list for your target

cat s3enum | sed 's/$1/<target>/g' 

Eg:- for tesla

cat s3enum | sed 's/$1/tesla/g'

Thankyou.
