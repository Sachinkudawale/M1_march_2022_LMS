
#  TEST PLAN:

# High level test plan

|TEST ID| DESCRIPTION| EXPECTED I/P|        Actual_Output|
| :-----|:-----------|:------------|-----------------------|
|HL01|Add Books|Category,Bookname,Author,Price| passs
|HL02|Delete Books|Category,id|pass
|HL03|Search Book|Category id|pass
|HL04|Issue Book|Category,id|pass
|HL05|View book|Category,id|pass


# Low level test plan

|TESTID| DESCRIPTION| EXPECTED I\P|
|:-----|:-----------|:------------|
|LL01|Adding Details of New Book|Category,Bookname,Author,Price|
|LL02|Deleting book by id & Category|Category,Id|
|LL03|Search for book by enter category,id|category,id|
|LL04|Issue based on id|category,id|
|LL05|View based on enter category,ID|category,id|