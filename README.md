# DownloadDoc

# Step 1 : To Order Data 
 
URL : https://technowire.in:5000/downloadsDoc

INPUT: Body: 

{"cin":"AAO-5663","apikey":"APIKEY","password":"PASSWORD"}


# Step 2 : Check Statuts and Download Link API

URL : https://technowire.in:5000/getcLatestTranscationAllApi

{"apikey":"API KEY","password":"PASSWORD"}


Response:

[
  {
    "id": 1909,
    "cname": "SOLLYWOOD CORPORATION PRIVATE LIMITED",
    "cin": "U45200GJ2012PTC070020",
    "p_txn": "CRDdz3vdy2rklb5ayeu",
    "status": "2",
    "pay_status": "1",
    "url": "https://s3.us-east-2.amazonaws.com/compdata.in/CIN/U45200GJ2012PTC070020.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAZJFO6I5MK5ARVFL3%2F20210218%2Fus-east-2%2Fs3%2Faws4_request&X-Amz-Date=20210218T183808Z&X-Amz-Expires=604800&X-Amz-SignedHeaders=host&X-Amz-Signature=9b4853b2ed34055b954500db4f665c040f3a51e54a3b6536fca1a3b762919ef1"
  },
  
  {
    "id": 1903,
    "cname": "TWS SYSTEMS PRIVATE LIMITED",
    "cin": "U72502DL2013PTC261372",
    "p_txn": "CRDdz3vbv3ukl63b327",
    "status": "2",
    "pay_status": "1",
    "url": "https://s3.us-east-2.amazonaws.com/compdata.in/CIN/U72502DL2013PTC261372.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAZJFO6I5MK5ARVFL3%2F20210222%2Fus-east-2%2Fs3%2Faws4_request&X-Amz-Date=20210222T162255Z&X-Amz-Expires=604800&X-Amz-SignedHeaders=host&X-Amz-Signature=28a8478117c4ec295e655573725d7a83668f4f167ccfd8efad732329a174d0f9"
  }
]


__________________________________________________________________________________________________
# Get API USer id And Password:
visit www.msmeintelligence.in
Signup -> Login -> Profile (Generate API Key ) -> SUBMIT

API Key : Derived Above
Password : Account Password

In Case you need any support contact us at +919033024545

