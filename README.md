Run the followings at https://replit.com/ in "Shell"

ပထမဆုံး သင့် https://console.cloud.google.com/ မှ credentials file ကို ယခု repo ရှိ credentials ထဲသို့ကူးပါ။

##ပုလုပ်ရန်အဆင့များ
၁
```
pip3 install -r requirements.txt
```
*pip update မလုပ်လဲရ*

၂
```
python3 generate_drive_token.py 
```
https:// လင့်ခ်ကို browser တွင် accept ပေးပါ။ console တွင်ဝင်ခဲ့သာ gmailဖစ်ရမည်

၃
```
python3 gen_sa_accounts.py --enable-services သင့်project name
```
https:// လင့်ခ်ကို browser တွင် accept ပေးပါ။ console တွင်ဝင်ခဲ့သာ gmailဖစ်ရမည်

၄
```
python3 gen_sa_accounts.py --create-sas သင့်project name
```

၅
```
python3 gen_sa_accounts.py --download-keys သင့်project name
```

**** ရလာတဲ့  account folders ထဲမှာ json ဖိုင်တွေရှိပါတယ်။ အဲ့ဒါကို emails ထုတ်ဖို့က 

```
python3 emails.py
```
## 📗 Pre-requisites:-
1. မိမိ
## ပြီးလျှင် repo တခုလုံးကို Download ပါ။ Download မလုပ်မီ အာက်ကပထားသာဖိုင်များကို MainData ထဲ အရင်ထည့ပါ။
.မိမိကွန်ပျူတာ သို့မဟုတ် ဖုန်း ထဲရောက်မှ zip ဖြည်ပြီး 
.accounts folder (contain 100 jsons)
.emails.txt
.credentials.json
.token.pickle
  ဖိုင်များကိုသိမ်းထားပါ။
