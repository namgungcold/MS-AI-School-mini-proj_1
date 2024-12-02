# MS_AI_School AI Search Project
본 프로젝트는 `MS Azure`를 활용하여 시행함<br>

## Data and Function
- **Data:**
  - `공공데이터포털`에 있는 '한국 농어촌 공사_계절테마여행정보.csv'를 활용한다.
  -  주제, 태그, 요약, 코스정보 등의 컬럼들이 존재한다.
  -  Data들을 Azure에서 저장 후 AI Search sercive에서 인덱스와 인덱서를 처리한다.
- **Function:**
  - GPT-4o를 사용하는 챗봇 기능을 한다.
  - 위 데이터를 `Fine-Tuning`하여 테마나 각 도를(ex. 경상북도, 전라남도, 강원도 등)입력하면 테마가 있는 여행을 추천한다.<br>
![1126_proj](https://github.com/user-attachments/assets/482d6ef1-2fe4-4241-aa28-96e5732155eb)

