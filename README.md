## Insertion Sort Projesi <br/>
**[22,27,16,2,18,6]** <br/>
**1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.** <br/>
1.Adım:22	27	16	2	18	6 <br/>
2.Adım:22	27	16	2	18	6 <br/>
3.Adım:22	16	27	2	18	6	-->	16	22	27	2	18	6 <br/>
4.Adım:.16	22	2	27	18	6	-->	16	2	22	27	18	6-->	2	16	22	27	18	6 <br/>
5.Adım:2	16	22	18	27	6	-->	2	16	18	22	27	6 <br/>
6.Adım:	2	16	18	22	6	27	-->	2	16	18	6	22	27 <br/>
6.Adım:	2	16	6	18	22	27	-->	2	6	16	18	22	27 <br/>


**2-Big-O gösterimini yazınız.** <br/>
O(n^2)

**3- Time Complexity** <br/>
[n*(n-1)]/2 : n^2 <br/>

**4- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.**<br/>
Avarage case. <br/>


**[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.**<br/>
1.Adım	7	3	5	8	2	9	4	15	6 <br/>
2.Adım	3	7	5	8	2	9	4	15	6 <br/>
3.Adım	3	5	7	8	2	9	4	15	6 <br/>
4.Adım	3	5	7	8	2	9	4	15	6 <br/>
