import pymysql
connection = pymysql.connect(host='5.183.188.132',user="db_vgu_student",password="thasrCt3pKYWAYcK",database="db_vgu_test")
with connection:
    cur = connection.cursor()
    cur.execute("SELECT * FROM category")
    rows = cur.fetchall()
    for row in rows:
        print(row)
