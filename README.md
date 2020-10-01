# yashrepo1
test repo1
g
import pandas
import DataFrame

def fetch_data():
    with open('dumpData.txt', 'r') as f:
        input_d = f.readline()

    print(input_d)
    st1 = int(input_d) - 1
    df = pandas.DataFrame(DataFrame.D,
                          columns=["id", "Sname", "marksInNet", "marksInDS", "marksInDBMS", "marksInandroid",
                                   "marksInAI", "marksInDataMining", "language1", "language2", "tools", "skill1",
                                   "skill2", "skill3", "seminarTopic", "projectTopic", "course1", "course2"])
    df1 = df.loc[st1]

    id = df1.id
    name = df1.Sname
    mInN = df1.marksInNet
    mInDS = df1.marksInDS
    mInDB = df1.marksInDBMS
    mInand = df1.marksInandroid
    mInAI = df1.marksInAI
    mInDM = df1.marksInDataMining
    language1 = df1.language1
    language2 = df1.language2
    tool = df1.tools
    skill1 = df1.skill1
    skill2 = df1.skill2
    skill3 = df1.skill3
    seminarTopic = df1.seminarTopic
    projectTopic = df1.projectTopic
    course1 = df1.course1
    course2 = df1.course2

    if mInDB >= mInN or mInDB >= mInDM or mInDB >= mInAI or mInDB >= mInand or mInDB >= mInDS:
        a = 1
    else:
        a = 0

    if "java" == language1 or "python" == language1 or "R" == language1 or "c++" == language1:
        b = 1
    else:
        b = 0

    if "java" == language2 or "python" == language2 or "R" == language2 or "c++" == language2:
        c = 1
    else:
        c = 0

    if "hadoop" == tool or "kafka" == tool or "hive" == tool or "pig" == tool:
        d = 1
    else:
        d = 0

    if "dataStructure" == skill1 or "sql" == skill1 or "linearAlgebra" == skill1 or "statistics" == skill1 or "java" == skill1 or "DBMS" == skill1:
        e = 1
    else:
        e = 0

    if "dataStructure" == skill2 or "sql" == skill2 or "linearAlgebra" == skill2 or "statistics" == skill2 or "java" == skill2 or "DBMS" == skill2:
        f = 1
    else:
        f = 0

    if "dataStructure" == skill3 or "sql" == skill3 or "linearAlgebra" == skill3 or "statistics" == skill3 or "java" == skill3 or "DBMS" == skill3:
        g = 1
    else:
        g = 0

    if "mapReduce" == seminarTopic or "bigData" == seminarTopic or "deepLearning" == seminarTopic or "sql" == seminarTopic or "kafka" == seminarTopic:
        h = 1
    else:
        h = 0

    if "mapReduce" == projectTopic or "bigData" == projectTopic or "deepLearning" == projectTopic or "sql" == projectTopic or "kafka" == projectTopic:
        i = 1
    else:
        i = 0

    if "java" == course1 or "spark" == course1 or "hadoop" == course1 or "hive" == course1:
        j = 1
    else:
        j = 0

    if "java" == course1 or "spark" == course1 or "hadoop" == course1 or "hive" == course1:
        k = 1
    else:
        k = 0

    z = a + b + c + d + e + f + g + h + i + j + k

    return z

def bdo():
    return fetch_data()


#strrr()


#.split()


#print(st)
#st1=int(st)
#v=type(st1)
#print(v)
#st=st.sort()
  #st=sorted(st)
  #st1=st[0]
#st2=int(st)
