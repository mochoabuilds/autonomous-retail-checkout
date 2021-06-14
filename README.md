# geaux

## 1 WHY?

* As the lines between banks, tech and retail blur we must ask how technology is changing the checkout experience and its overall flows of data.  _Our proof of concept explores how autonomous checkout could be "gifted" to others as an experience to make the idea of "the new" more palatable._

*  As the next great experiment in payments technology comes, retailers in cities may need to prepare for a long-term shift in how money and checkout works.  _Our code runs on the idea that "people don't want to make payments, they want to do what a payment facilitates".  Future shoppers will want choice.  Sometimes they will want autonomous-checkout and sometimes they will want to checkout with a cashier._  Our proof of concept automates the dull and repetitive tasks of scanning goods by bridging two cameras, a processor, many lines of code and much data.  This mix gives workers some more freedom from the register, so they can focus on those other things that create loyal regulars and that "third place" vibe in their space. Our real moonshot is to _normalize the idea of shoppers depositing funds directly with a retailer, then "gifting" autonomous checkout experiences at that retailer directly to friends, family and coworkers on a Venmo-like platform._

* Imagine "gifting" your friend an autonomous-checkout experience. They walk into the retailer, they "check in" with their smartphone, they browse, they walk out. This "gifting" approach means transactions could also be settled instantly on in-house digital ledgers via Cash/etc, rather than the pipes of cards networks and banks.  By pulling transactions out of the banking system we cut operating expenses for retailers, which amount to 1-3% per transaction.  This approach also ensures retail payment infrastructure has a back-up system in the event power outages or cyber-attacks cause traditional payment channels to fail.  

## 2 RESEARCH GOALS

* As with any AI and machine learning learning, the syllabus determines the outcome.  Our syllabus is focused on the political value of time at retail checkout that we may have not considered ourselves.  
* We build our AI system to think like an ethnographer, very sensitive to the members meaning filling each respective space.  The subroutines are written to make sure the biases of the analog world are not repeated in the AI and machine learning world.  Questions such as - who benefits and who is harmed by this application?  And does it put power into the hands of the already powerful? - are asked repeatedly at every step in the software development process.  This approach to development ensures diversity and sustainability is activel built in at every step of the system.
* Additionally, this project was created to showcase my ability to write software, even with my missing per-requisite coursework, and design marketable products competently at the graduate level. 

## 3 HOW? 

* 1 - ASK "WHAT SYSTEM MUST DO" by analyzing problem with shoppers and experts in the field to determine what is required of solution
* 2 - MODEL REQUIREMENT for OBJECTS using bottom-up approach that looks for objects that closely model the real world
* 3 - NAME the CLASSES and METHODS that carry out these RESPONSIBILITIES from step 2 
* 4 - REFINE the CLASS INTERFACE and DETERMINE: CLASSNAME, RESPONSIBILITIES and COLLABORATOR CLASSES to build cohesion
* 5 - DEVELOP the MESSAGE SENDING PROTOCOLS using step 4 as starting point and determine what types of arguments need to be sent with a message and what type of object a method can return.  Here is where we also document preconditions and postconditions, that solidify are the responsibilities of the class. 
* 6 - SETUP the CLASS FRAMEWORKS for testing newly identified classes to make sure components integrate and fulfill our goals
* 7 - TEST CLASS INTERFACE and "add some flesh" to step 6 by sending message sending protocol to class interface before developing the methods
* 8 - FILL in the METHODS and CLASS ATTRIBUTES for each class to make sure object's methods work 
* 9 - TEST, DEBUG AND INTEGRATE all the parts :)

## 4 CORNER STORE v-1 DATASET

ACTIONS / OBJECTS TRACKED
  * Items in Store (~80)
  * Single Handed Pulls of Items From Shelf
  * Double Handed Pulls of Items From Shelf
  * Hand Offs of Items Between People
  * Non Shelf Pulls of Items
  * Tosses of Items Between People
  * Misplaced Items 
  * Final Item Inventory and Checkout
  * This dataset is a growing list.  It is mainly focused on scenarios that require long range temporal reasoning for differentiation.  Other scenarios focus more on the object-action relationship, such as people pulling itmes from a shelf. This current dataset has 100 action-object classes, with 100 clips for each action and each clip running approx 10 seconds. In total the v1 dataset has 10,000 videos. It should be noted that all clips collected have variable resolution and frame rates.

## 4 "PRETRAINING"

* We use an offshoot of ImageNet model to pre-train our system. We are immensely grateful for ImageNet and the human labor it took to sort, label and prep the millions of images across thousands of categories. Pre-training helps us avoid representational bottlenecks, boost our activations per tile and better balance the width and depth of the network.  What's more this approach helps us better understand how to model spatio-temporal cues at different scales across multiple cameras.

## 5 ADDRESSING DATA BIAS

## 6 ANALYSIS, DESIGN & IMPLEMENTATION 

## 7 TRAINING DETAILS

* Learning Rates 
* Additional Data Prep
* Testing

## 8 EXPERIMENTS

* In this section we explore the accuracy and generalization of models on different benchmark data sets. 
* Accuracy = Repeatability + Calibration

## 9 RESULTS

## 10 MEASURING ACCURACY ACROSS BENCHMARK DATASETS

* UCF-101 DATASET - 13320 videos across 101 action classes
* Accuracy:
* HMDB-51 DATASET - 6766 videos across 51 action classes
* Accuracy:

## 11 DISCUSSION

## APPENDIX A: "CORNER STORE v-1" EXPANDED

## ACKNOWLEDGEMENTS

* This work was supported by my immediate family, close friends, confidants, my neighborhood grocers/corner stores and the open source community. 

## SANDBOX

* Teaching computer vision systems NOT to use guest biometrics as a condition of accepting payment under the Song Beverley Act of 1971
* Determining the metrics that improve downstream performance
* Better understanding the front-back orientation of human limbs due to clothing, lighting, background, optical interference
* "What You Almost Bought" Merchant Facing Application
* Bridging the edge-cloud barrier to lower server costs?
* Rewriting code and making arrays more ergonomic
* Lowering the costs of switching data across different corner stores
* Better understanding how social, economic and legal systems work together to achieve goals

## REFERENCES

* Writing Ethnographic Field Notes, 2nd Edition (2011)
* The Great Good Place by Roy Oldenburg (1989)
* 
* C++ for Business Programmers
* Building Business Applications Using C++
* Open Source Computer Vision for Beginnners: Learn OpenCv using C++ (2017)
* Learning OpenCV 3: Computer Vision in C++ with the OpenCV Library (2017)
*
* "Quo Vadis, Action Recognition? A New Model and the Kinetics Dataset" (2018)
* "The Kinetics Human Action Video Dataset" (2017)
* "Two Stream Convolutional Networks for Action Recognition in Videos" 
* 
* "Towards Good Practices for Very Deep Two-Stream ConvNets" (2015)
* "FlowNet 2.0: Evolution of Optical Flow Estimation with Deep Networks" (2016)
* 
* "Going Deeper with Convolutions" (2014)
* "Rethinking the Inception Architecture for Computer Vision" (2015)
