# Singlecell_final


file_path = 'C:/Users/chris/Downloads/singlecell_result/final_Result'  
경로를 해당 부분에서 수정하고, raw data도 해당 경로에 다운로드 받아야 스크립트가 돌아갑니다.  

<final_10samples_PAGA_cor.ipynb>  
Result 1) HNSCC 에서는 Epithelial cell의 p-EMT program이 발현이 나타난다 : Tajectory inference결과를 볼 수 있습니다.  
Result 3) p-EMT는 Wnt, Hh 시그널링을 up-regulation하지 않는다 : EMT gene 80개에 대하여 분석한 결과를 볼 수 있습니다.  

<final_5samples_malignant_LN_pemt.ipynb>    
Result 2) HNSCC에서 p-EMT는 Lymph node전이의 원인이 될 수 있다 : 두 번째 결과에 대한 분석입니다.    
 
<final_malignant_CAF_sample25.ipynb>    
<final_malignant_CAF_sample5_.ipynb>    
Result 3) p-EMT는 Wnt, Hh 시그널링을 up-regulation하지 않는다    
(raw데이터에서 scanpy를 사용할 필요가 없긴 하지만,  
scanpy의 전처리 과정에서 제거되는 cell들을 동일하게 삭제해 주기 위하여 사용하였습니다.) 


=> primary tumor의 malignant 세포와 CAF(5번 샘플, 25번 샘플)들을 스크립트마다 각각 불러왔고,  
그 중 malignant 세포의 p-EMT발현량과 모든 gene들의 상관분석을 진행하였으며  
malignant cell과 CAF 사이의 리간드-리셉터 분석을 위한 파일을 만들었습니다.  
cell-linker를 위해서는 결과로 나온 파일에서 약간의 수정이 필요한데,  
meta data에서는 header를 지워주고 tpm파일에서는 맨 앞의 tab을 지워주면    
cell-linker 웹 페이지에 업로드 할 수 있는 상태가 됩니다.   

- 레포트에 다 올리지 못한 데이터들은 메일과 github에 첨부하겠습니다.

- raw data 파일은 용량이 커서 올릴 수 가 없습니다.  
아래의 사이트에서 Supplementary file를 보시면 다운로드 받을 수 있습니다.  
https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE103322
