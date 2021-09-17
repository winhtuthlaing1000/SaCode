Run the followings at https://replit.com/ in "Shell"

ပထမဆုံး သင့် https://console.cloud.google.com/ မှ credentials file ကို ယခု repo ရှိ credentials ထဲသို့ကူးပါ

## 💠ပြုလုပ်ရန်အဆင့်များ
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
## 📙 ပြီးလျှင် repo တခုလုံးကို Download ပါ။ Download မလုပ်မီ ​အောက်ကပြထားသာဖိုင်များကို MainData ထဲ အရင်ထည့်ပါ
1. accounts folder (contain 100 jsons) 
2. emails.txt 
3. credentials.json 
4. token.pickle ဖိုင်များကိုသိမ်းထားပါ။
    ✅မိမိကွန်ပျူတာ သို့မဟုတ် ဖုန်း ထဲရောက်မှ zip ဖြည်ပြီး သိမ်းပါ✅
    
# ဆက်သွယ်ရန်
[Bot Tutorials Channel](https://t.me/BotTutorialsMM)

[ContactMe](https://t.me/Dr007bot)
