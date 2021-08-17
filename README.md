Run the followings at https://replit.com/ in "Shell"

ပထမဆုံး သင့် https://console.cloud.google.com/ မှ credentials file ကို ယခု repo ရှိ credentials ထဲသို့ကူးပါ။

၁- pip3 install -r requirements.txt

၂- py generate_drive_token.py    (run with python3  or py)
https:// လင့်ခ်ကို ကူး browser တွင် accept ပေးပါ။

၃- py gen_sa_accounts.py --enable-services သင့်project name
https:// လင့်ခ်ကို ကူး browser တွင် accept ပေးပါ။

၄- py gen_sa_accounts.py --create-sas သင့်project name

၅- py gen_sa_accounts.py --download-keys သင့်project name


**** ရလာတဲ့  account folders ထဲမှာ json ဖိုင်တွေရှိပါတယ်။ အဲ့ဒါကို emails ထုတ်ဖို့က 

type 

py emails.py

ပြီးလျှင် repo တခုလုံးကို Download ပါ။
မိမိကွန်ပျူတာ သို့မဟုတ် ဖုန်း ထဲရောက်မှ zip ဖြည်ပြီး 

-accounts folder (contain 100 jsons)
-emails.txt
-credentials.json
-token.pickle
ဖိုင်များကိုသိမ်းထားပါ။
