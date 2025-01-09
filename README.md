
DecisionTree | 
For titanic to give 78.78% accuracy you should change
the params to :
if __name__ == "__main__":
 #dataset = "titanic"
 dataset = "spam"
 params = {
 "max_depth": 5,
 "min_samples_leaf": 40,
 "criterion": "entropy",
 }
 N = 10
For spam to give 80.20% accuracy you should change the
params to:
if __name__ == "__main__":
 #dataset = "titanic"
 dataset = "spam"
 params = {
 "max_depth": 5,
 "min_samples_leaf": 40,
 "criterion": "entropy",
 }
 N = 20
 


E2EE File Sharing System | Golang : https://gitfront.io/r/fauti/oKjwY9KgsX5P/A-Secure-File-Sharing-System/


Traceroute Implementation | Python : https://gitfront.io/r/fauti/NiiJwJpbmmrC/project2-traceroute-Fatemeh110/


Concurrency Control and Lock Management System | java, Database Systems : https://gitfront.io/r/fauti/hymZXTT1arkK/Concurrency-Lock/
