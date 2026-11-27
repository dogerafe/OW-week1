First exercise

Tried first exercise of creating a dataset.
I thught about who I was and figured to other people its the things that I do in my free time.
I have played a lot of sports in my life and thought it would make enough data.
I wrote out the sports that I have played and how lomg I played them for.
I struggled to figure out what I was supposed to do to submit it for a bit.
I figured out how subfolders worked..
I figured out how to add a spreadsheet to Github on google.
Data could be a lot more complex adding actual game stats is an option as thye do exist for hockey.
Could add gear types for each sport or locations which are also known.

Second exercise: Documents-to-structured-data with Python, using Google Colab

Stop!!!
School wifi sucks.
2 errors, ERROR: Could not find a version that satisfies the requirement torchaudio (from versions: none)
ERROR: No matching distribution found for torchaudio.
now im going to try again.
waiting again.
it didnt work again.
IM going to try ine more time before i move on to a different exercise.
some more waiting.
It didnt work again but I found this other error ERROR: pip's dependency resolver does not currently take into account all the packages that are installed. This behaviour is the source of the following dependency conflicts.
torch 2.11.0+cu128 requires nvidia-cudnn-cu12==9.19.0.56; platform_system == "Linux", but you have nvidia-cudnn-cu12 9.5.1.17 which is incompatible.
torch 2.11.0+cu128 requires nvidia-cusparselt-cu12==0.7.1; platform_system == "Linux", but you have nvidia-cusparselt-cu12 0.6.3 which is incompatible.
torch 2.11.0+cu128 requires nvidia-nccl-cu12==2.28.9; platform_system == "Linux", but you have nvidia-nccl-cu12 2.25.1 which is incompatible.
Im going to reread the instrution son github one more time and if I cant fin the reason this is happening im not going to commit more time to this.

Coming back to the second exercise:
I am starting the blocks up again. Another error popped up:
ERROR: pip's dependency resolver does not currently take into account all the packages that are installed. This behaviour is the source of the following dependency conflicts.
ipython 7.34.0 requires jedi>=0.16, which is not installed.
paddlex 3.7.2 requires numpy<2.4,>=1.24, but you have numpy 2.5.2 which is incompatible.
paddlepaddle-gpu 3.3.0 requires nvidia-cublas==13.0.2.14; platform_system == "Linux" and platform_machine == "x86_64", but you have nvidia-cublas 13.1.1.3 which is incompatible.
paddlepaddle-gpu 3.3.0 requires nvidia-cuda-runtime==13.0.88; platform_system == "Linux" and platform_machine == "x86_64", but you have nvidia-cuda-runtime 13.0.96 which is incompatible.
paddlepaddle-gpu 3.3.0 requires nvidia-cudnn-cu13==9.13.0.50; platform_system == "Linux" and platform_machine == "x86_64", but you have nvidia-cudnn-cu13 9.24.0.43 which is incompatible.
paddlepaddle-gpu 3.3.0 requires nvidia-nccl-cu13==2.28.3; platform_system == "Linux" and platform_machine == "x86_64", but you have nvidia-nccl-cu13 2.30.7 which is incompatible.
paddlepaddle-gpu 3.3.0 requires nvidia-nvjitlink==13.0.88; platform_system == "Linux" and platform_machine == "x86_64", but you have nvidia-nvjitlink 13.3.33 which is incompatible.
gcsfs 2025.12.0 requires fsspec==2025.12.0, but you have fsspec 2026.7.0 which is incompatible.
numba 0.61.2 requires numpy<2.3,>=1.24, but you have numpy 2.5.2 which is incompatible.
datasets 4.8.5 requires fsspec[http]<=2026.2.0,>=2023.1.0, but you have fsspec 2026.7.0 which is incompatible.
cuda-python 13.0.3 requires cuda-bindings~=13.0.3, but you have cuda-bindings 13.3.1 which is incompatible.
 I am going to try and run block 2 anyways. Seems like it still works so I am moving on to block 3 which will feed images into the model from the archaeology data service. adding hte other blocks is very interesting to see it come together finally. I think taht this will be useful when i take hand notes resaerching mt PDAP.
Third exercise: Build a recording sheet with Kobotoolbox

Account created..
This was much simpler
went much smoother.
Screenshots are in a file on my computer.

Week 3 at the Billings estate notes.

i didn't know how to use kobotoolbox and got rid of all of the stuff that I put in there so I will now try to replicate it all based on a photo that I took of the grave.
using the LIDAR gun was interesting but it stopped me from being able to take an actual sketch map so I mostly just doodled on the paper which I will upload to my github the doodles are not very good.

much less was done than what was planned so I do not have as much to show what I have done as I wished that I had.
photogrammerty was quite interesting but I dont think I took wnough photos for a full image I will try to make one anyways.
it would have been cool to use the 3d scanner but I did not get to use it.

Week 4 GIS Lab

Archaelolgy spatial data Lithgow exercise.
Google collab is working well nothing has goe wrong so far just following instructions.
Gotten to a photograph of the placement of the bodies, Changing the word that equals the CMAP changes the color of the bodies on the map
Just typing Lithgow_Burials is enough to print out all of the data on the coding notebook, very interesting this must be becuase of the basic tools added in the beginning.
Panda helps with the use of spreadsheet data, adding small additions to the code is enough to change how the information is visualized.
With the given data you can insert code to specify what data you represented in a image and also the spreadsheet.
If i become an archaeologist I will avoid using a local grid.

For the GIS lab assignment I did not add it to my repository at the end of class but I will try and go back to see if I can retrieve it next week.
I do remember that there was supposed to be an error in the GIS lab exercise but it actually did not happen for me.
I did have an error at the end the school blocked the other applications for the GIS software so I was not able to augent my map in a certain way.

Week 6

Collab notebook in R this time. 
Good looking data spread.
It is interesting to see the difference between python and r code.
The other data frame that I added was Upper Paleolithic Engraved Bone Design Elements - Spain and I just copy pasted what the website said to to see what it would look like. I will add a photo for this.
I then used Bronze Age Cups from Italy to create a graph which is added also.
If the P value is 0.02 then the null hypothesis is rejected.
I think that there could be an association between age and presence of goods.
I am enjoying using R I did a chi squared test on the BA cups data that did not reject the null.
I made a barplot of the grave latitudes that will be added also.

Harris matrix stuff The first matrix was confusing and i think that I did it wrong but after looking at the second matrix example I understand how the matrix works, the contexts are done in order of what is found when it is excavated, usually first its the object then the fill then the whole itself before the next object is moved on to, the readings for the third exercise taught me that each group is each hole and subgroups are related to speceifc details within the group and phases are all encompassing things that include each group, I will take all o f  this information when doing exercise 3. What I do not understand is how things are labelled and also 


Week 7

Collab notebook.
everything is goin quickly now past the first tree things.
The CSV file seem to be data about the map, towns and roads coasts and overseas stuff.
Very interesting network that was put together here with around 7-10 hotspots.
Error when calculating the degree because name Networkx is not defined.
I have to change the name but I do not know how to. 
Changing the name to nx.degree worked I found that after looking it up.
Orderin the degrees of the cities show that the ones that have the most are ancient greek implying that civilization had a large impact on culture.
The cities are well connected so they must have been bery important in ancient grece for culture and other things of that nature.
Also error on betweenness centrality changing the name to nx.betweeness_centrality worked again,
modularity and communities interesting stuff here.

Network navigator tool
idk how this works I did not pay attention in class I was studying for the midterm for my other class that same day.
I have absolutely zero idea as to how to do this.


Week 8














