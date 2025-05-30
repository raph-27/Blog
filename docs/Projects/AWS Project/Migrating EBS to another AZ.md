<h2 style="text-align: center;">Example Architectural Diagram </h2>
<img src="../../../assets/Snapshot Migration/Example Architectural Diagram.png"  width="1000" height="500"/> <br><br>
First we need to create a volume that we want to migrate to another region
<img src="../../../assets/Snapshot Migration/Create Volume.png"  width="1000" height="500"/> <br><br>
select the volume that we want to migrate and `Create Snapshot`
<img src="../../../assets/Snapshot Migration/Create Snapshot.png"  width="1000" height="500"/>
<img src="../../../assets/Snapshot Migration/Create Snapshot 2.png"  width="1000" height="500"/>
If we go to the Snapshot GUI, we can see the snapshot that we created
<img src="../../../assets/Snapshot Migration/Create Snapshot 3.png"  width="1000" height="500"/> <br><br>
Select the snapshot that we created and `Right Click` and click `copy Snapshot`
<img src="../../../assets/Snapshot Migration/Copy Snapshot.png"  width="1000" height="500"/> <br><br>
Since we are in region `us-east-1 or N.Virginia` we need to select another region, in this case I choose `us-east-2 or Ohio`
<img src="../../../assets/Snapshot Migration/Copy Snapshot 2.png"  width="1000" height="500"/> <br><br>
After I change my region on the upper right corner, I selected `Ohio` on the dropdown list. As we can see, The Snapshot that we copied from `us-east-1 or N.Virginia` is now available in the `us-east-2 or Ohio`
<img src="../../../assets/Snapshot Migration/Copy Snapshot 3.png"  width="1000" height="500"/> <br><br>
Select the migrated Volume and select `create a volume from snapshot`
<img src="../../../assets/Snapshot Migration/create volume from snapshot.png"  width="1000" height="500"/> <br><br>
Configure the settings that we want 
<img src="../../../assets/Snapshot Migration/create volume from snapshot 2.png"  width="1000" height="500"/> <br><br>
And It's done, we can attached this volume
<img src="../../../assets/Snapshot Migration/done.png"  width="1000" height="500"/> <br><br>
