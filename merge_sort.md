# [16,21,11,8,12,22] -> Merge Sort
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız

> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[16,21,11,8,12,22] <br>
> &nbsp;&nbsp;&nbsp;&nbsp; [16,21,11] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;     [8,12,22] 
> &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <br>
> &nbsp;&nbsp;&nbsp;[16] [21,11]&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;     [8,12] [22] <br>
>&nbsp;&nbsp;[16] [21] [11]&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  [8] [12] [22] <br>
>&nbsp;&nbsp;&nbsp; [16] [11,21] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  [8,12] [22] <br>
> &nbsp;&nbsp;&nbsp;&nbsp; [11,16,21] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  [8,12,22] <br>
>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [8,11,12,16,21,22] <br>

Big-O gösterimini yazınız.
> O(nlogn)