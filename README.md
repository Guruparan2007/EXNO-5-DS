# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.



Name: Guruparan G

Register No:212224220030


# Coding and Output:
 python
python
height=[10,24,36,37,45]
names=['one','two','three','four','five']
c1=['red','blue']
c2=['b','g']
plt.bar(names,height,color=c1,width=0.8)
plt.xlabel("names")
plt.ylabel("height")
plt.title("BAR CHART")
plt.show()


![image](https://github.com/user-attachments/assets/a5b7d71c-62d8-4e56-baa9-fe3d7affe05d)
python
x=[2,8,10]
y=[11,16,9] 
x2=[3,9,11] 
y2=[6,15,7]
plt.bar(x, y,color='yellowgreen') 
plt.bar(x2, y2, color = 'purple')
plt.title("Bar graph")
plt.ylabel('Y axis')
plt.xlabel('x axis')
plt.show()


![image](https://github.com/user-attachments/assets/38219006-1b9f-43aa-aae5-7c6bc6fc5258)
python
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0, 100)
bins=10
plt.hist(ages, bins, range, color='cyan', histtype='bar', rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No. of people')
plt.title('Histogram')
plt.show()


![image](https://github.com/user-attachments/assets/431ea6bf-d3e2-4848-b797-2b9d4f51516b)
python
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins=10, color='blue', alpha=0.5)
plt.show()



![image](https://github.com/user-attachments/assets/99fefd74-333a-463a-ab6f-726ec7cecf15)
python
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data


![image](https://github.com/user-attachments/assets/03d8540f-60ae-468d-9ae0-f56e0e16f7b9)
python
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_title("BOX PLOT")
ax.set_ylabel("Y-AXIS")
ax.set_xlabel("X-AXIS")


![image](https://github.com/user-attachments/assets/765b76af-0126-460c-b2fa-64c3e8b44570)
python
activities = ['eat', 'sleep', 'work', 'play']
slices=[3, 7, 8, 6]
colors = ['r', 'y', 'g', 'b']
plt.pie(slices,labels=activities,colors=colors,startangle=90, 
        shadow=True,explode=(0,0,0.1,0), radius=1.2, autopct='%1.1f%%')
plt.legend ()
plt.show()


![image](https://github.com/user-attachments/assets/b56e792a-957c-44bb-b4df-b2648ea9f30a)
python
labels=['Python','C++','Ruby','Java']
sizes=[215, 130, 245, 210] 
colors=['gold', 'yellowgreen', 'lightcoral', 'lightskyblue'] 
explode=(0,0.4,0,0.5)
plt.pie(sizes, explode=explode, labels=labels, colors=colors, autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()


![image](https://github.com/user-attachments/assets/64d715a0-e308-4fc7-8ef3-b08e1a1c9bf8)



# Result:
 Thus program runs successfully and verified
