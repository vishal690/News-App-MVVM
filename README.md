# News-App-MVVM

<h3>Application which retrieves data from Webserver (via Retrofit), saves it into Room. <br/>
There are applying MVVM architecture pattern. </h3>
<h3>Overview: </h3>
<ul>
<li><h3>Model</h3>
Model is implemented as Repository pattern. Firstly it begins from internet connection checking. Consequently if it's alive we're retrieving data from the server (by using Retrofit 2).
</li>
<li><h3>View</h3>
View is realised as 2 fragments. First one contains RecyclerView, second one depends on clicks on recycler-items and finally displays detailed data fetched from the Model.
It implements state saving reflected on configuration changes.
</li>
<li><h3>ViewModel</h3>
ViewModel is responsible for transferring data between view and model.
</li>
</li>
</ul>
<hr/>

<h3> Applied technologies and libraries: </h3>
<ul>
<li><h3>Model</h3>

<h4><i>Retrofit 2</i></h4> - getting data from server into pojo-classes
<h4><i>Coroutines</i></h4> 
   - managing asynchronous database and network queries<br/>
   - using instead of callbacks<br/>
   - providing light asynchronous operations
</li>	 
<li><h3>ViewModel</h3>
<h4><i>LiveData</i></h4> - observer-pattern implementation for View interaction
</li>

<li><h3>View</h3>
<h4><i>Fragments</i></h4> 
   - interactive displaying and click reflecting
<h4><i>Data Binding</i></h4>
   - replace basic operations with UI (e.g. findViewById() ) to the XML
</li>
</ul>


# ScreenShort

![breakingNewsScreen](https://user-images.githubusercontent.com/100077067/209288006-4a258064-65e1-439a-9689-6878146a158c.jpg)
![saveNewsScreen](https://user-images.githubusercontent.com/100077067/209288014-5c6a969a-0bbf-4865-a2ea-791311db19a2.jpg)


![searchNewsScreen](https://user-images.githubusercontent.com/100077067/209288024-09d95d31-e8e6-4a2a-a55e-0df912517484.jpg)
![webViewScreen](https://user-images.githubusercontent.com/100077067/209288029-98104083-5bac-4f3c-b73a-279d0a8c125a.jpg)



# Video Sample





https://user-images.githubusercontent.com/100077067/209288733-a0ce8562-b666-4b0c-a30a-0756708a771c.mp4



