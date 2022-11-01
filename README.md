# Insurance Management

---
## screenshots
### Homepage
![homepage snap]![image](https://user-images.githubusercontent.com/87440737/195431347-22084b76-9061-4751-8724-de7df1c7bfce.png)

### Admin Dashboard
![dashboard snap]![image](https://user-images.githubusercontent.com/87440737/195431522-6694dcd9-6256-4461-9ca9-a1e19151ba97.png)
### Policy Record
![invoice snap]![image](https://user-images.githubusercontent.com/87440737/195431800-061df65e-908a-41d1-946f-979a14df8086.png))
### Policy 
![doctor snap]![image](https://user-images.githubusercontent.com/87440737/195431958-fd29c656-ffe0-4180-a534-26d109c20c4c.png)
---
## Functions
### Admin
- Admin account can be created using createsuperuser command.
- After login, admin can view/update/delete customer
- Can view/add/update/delete policy category like Life, Health, Motor, Travel
- Can view/add/update/delete policy
- Can view total policy holder, approved policy holder, disapproved policy holder
- Can approve policy, applied by customer
- Can answer customer question

### Customer
- Create account (no approval required by admin)
- After login, can view all policy that are added by admin.
- If customer likes any policy, then they can apply for it.
- When customer will apply for any policy, it will go into pending status, admin can approve it.
- Customer can check status of his policy under history section
- Customer can ask question from admin. 

---

## HOW TO RUN THIS PROJECT
- Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
- Open Terminal and Execute Following Commands :
```
python -m pip install -r requirements.txt
```
- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :
```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```

```
owner are Shivani Gupta,Akshada Golhe,Krishna Khandelwal

....
