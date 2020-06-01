#trigger createcontact on Account
List <contact> con = new List <contact>();
        
        for (Account acc : Accounts)
        {
            contact con1 = new contact();
            con1.LastName = 'Kumar';
            con1.AccountId= acc.id;
            con.add(con1);  
        }
        insert con;
