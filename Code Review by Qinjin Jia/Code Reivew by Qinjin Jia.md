# EC601_Code Review :mag:
## Brief Introduction :sunglasses:
  Hello Everyone! :trollface::trollface::trollface::trollface:
  
  This is the page for **EC601(Fall 2017) A1 Code Review Assignment** :loop:
  
  |The project reviewed| **[@github.com/kev5/Go-Meet](https://github.com/kev5/Go-Meet)**
  |--|--
  |**The Reviewer**| :boy: **Qinjin Jia** qjia@bu.edu   :point_right:[@github/qinjinjia](https://github.com/qinjinjia)
  |**Criteria Followed**| [MIT 6.005 fall 15 - Reading 4 Code Review](http://web.mit.edu/6.005/www/fa15/classes/04-code-review/) 
  ||[Code Review Checklist](http://www.evoketechnologies.com/blog/code-review-checklist-perform-effective-code-reviews/)

  :sun_with_face: Summary of the Code Review Criteria :link: [Code Review Criteria.pdf](https://github.com/qinjinjia/ec601_Code-Review/blob/master/Code%20Review%20by%20Qinjin%20Jia/Code%20Review%20Criteria.pdf) 
 
 :full_moon_with_face: Code Review auxiliary tool: [jslint](http://www.jslint.com)
 
## Overall
 :new_moon_with_face: This is an exciting project **[Go & Meet](https://github.com/kev5/Go-Meet)**. The project is essentially a **social/recreational application** which gives information of all the events  (public/private) happening in the local vicinity of the user on a real-time basis.
 
 :new_moon: The Github Repository of the Project **[Go & Meet](https://github.com/kev5/Go-Meet)** is abundant and **there is a ReadMe file in the repository, which is perfect**.
 
 :waxing_crescent_moon: However, there are many files in the Repository and **GitHub file structure and directory structure is not clearly understandable**. It seems that it is because the project is still under development :construction:. 

 :first_quarter_moon: There are ten java files I reviewed:
          
 |File Name |Link |
 |--|--
 |ChooseLoginRegistrationActivity.java|:link: [ChooseLoginRegistrationActivity.java](https://github.com/kev5/Go-Meet/blob/master/ChooseLoginRegistrationActivity.java)|
 |Community.java|:link: [Community.java](https://github.com/kev5/Go-Meet/blob/master/Community.java)|
 |Database.java|:link: [Database.java](https://github.com/kev5/Go-Meet/blob/master/Database.java)|
 |LoginActivity.java|:link: [LoginActivity.java](https://github.com/kev5/Go-Meet/blob/master/LoginActivity.java)|
 |MainActivity.java|:link: [MainActivity.java](https://github.com/kev5/Go-Meet/blob/master/MainActivity.java)|
 |Post.java|:link: [Post.java](https://github.com/kev5/Go-Meet/blob/master/Post.java)|
 |RegistrationActivity.java|:link: [RegistrationActivity.java](https://github.com/kev5/Go-Meet/blob/master/RegistrationActivity.java)|
 |User.java|:link: [User.java](https://github.com/kev5/Go-Meet/blob/master/User.java)|
 |readFromFireBase.java|:link: [readFromFireBase.java](https://github.com/kev5/Go-Meet/blob/master/readFromFireBase.java)|
 |writeToFireBase.java|:link: [writeToFireBase.java](https://github.com/kev5/Go-Meet/blob/master/writeToFireBase.java)|
          
## Code Review

### 1. Code Formatiing

#### 1.1 Alignments
The uses of alignments are perfect. The code block starting point and ending point are easily identifiable.

#### 1.2 Naming Conventions
The ‘camelCode’ nameing convention is used in the project. The developers utilize capital letters to indicate the start of a word, which makes name of variables are meaningful.

#### 1.3 Code Layout
Perfect! The code can fit in the standard 14-inch laptop screen.

#### 1.4 Commented Code
It seems that it is because the project is still under development :construction:. There are some commented code blocks in the project.

For instance, the commented code in [Database.java](https://github.com/kev5/Go-Meet/blob/master/Database.java) should be delected (Or moved from the master branch).   
```
public class Database {
    public FirebaseDatabase mDatabase;
    public DatabaseReference myRef;
//    public String ID = "690";   <-This commented code should be removed
    public Database(){
    }
```
and the commented code in [MainActivity.java](https://github.com/kev5/Go-Meet/blob/master/MainActivity.java) should be removed.
```
        al.add(post01.getPostText());
//        al.add(post02.getPostText());
//        al.add(post03.getPostText());
//        al.add(post04.getPostText());
//        al.add(post05.getPostText());
//        al.add(post06.getPostText());
```

</br>

### 2. Architecture

</br>

### 3. Coding best practices

#### 3.1 Hard Coding
Good!. There is no hard coding in the project.

#### 3.2 Enumeration

        mWrite.writePosts("1",post01);
        mWrite.writePosts("2",post02);
        mWrite.writePosts("3",post03);
        mWrite.writePosts("4",post04);
        mWrite.writePosts("5",post05);
        mWrite.writePosts("6",post06);
        
#### 3.3 Comments

#### 3.4 Mul if/else blocks

#### 3.5 Framework features

</br>

### 4. Non Functional requirements
#### 4.1 Maintainability
#### 4.2 Reusability
#### 4.3 Reliability:
#### 4.4 Extensibility
#### 4.5 Security
#### 4.6 Performance
#### 4.7 Scalability
#### 4.8 Usability

</br>

### 5. Object-Oriented Analysis and Design (OOAD) Principles

#### 5.1 Single Responsibility Principle(SRS)
#### 5.2 Open Closed Principle
#### 5.3 Liskov substitutability principle
#### 5.4 Interface segregation:
#### 5.5 Dependency Injection:

## Summary
### Good Points:
### Can be better:

**Finally, Good Luck for your project :D)**:exclamation:

:trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface:
