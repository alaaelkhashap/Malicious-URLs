# Malicious-URLs
![image](https://user-images.githubusercontent.com/60587913/209418918-71cecc0a-f1f3-4eac-8ac8-b0b4793a61d9.png)

## Problem defination
Recent years have seen a sharp rise in cybersecurity assaults on many websites throughout the world, including ransomware, phishing, malware injection, etc. As a result, several financial institutions, e-commerce businesses, and people suffered significant financial losses. Since new attack types are being developed daily, controlling a cyber security attack in such a situation is a significant problem for cyber security specialists. malicious URL or website generally contains different types of trojans, malware, unsolicited content in the form of phishing, drive-by-download, spams.

## Dataset
you can download dataset from https://www.kaggle.com/datasets/sid321axn/malicious-urls-dataset

* Dataset description
    In this case study, we will be using a Malicious URLs dataset of 6,51,191 URLs, out of which 4,28,103 benign or safe URLs, 96,457 defacement URLs, 94,111 phishing URLs, and 32,520 malware URLs.

### The various URL types in our dataset:

>  phishing URLs: Hackers attempt to get sensitive personal or financial information, such as login credentials, credit card numbers, internet banking information, etc., by generating phishing URLs.


> Benign URLs: These are secure links to browse.

> Defacement URLs: Hackers typically generate defacement URLs with the goal of getting into a web server and replacing the hosted website with one of their own.

> Malware URLs: When a victim visits one of these URLs, malware is introduced into the victim's system.

## Methodology
* Feature extraction
  - having_ip
  - count_dot
  - AtSign
  - google_index
  - no_director
  - no_embed_domain
  - num_digits
  - len_url
  - num_parameter
  - num_fragments
 * Models
  - RandomForestClassifier
  - LGBMClassifier




