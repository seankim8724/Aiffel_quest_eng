# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김효찬
- 리뷰어 : 김동건


# PRT(Peer Review Template)
- [o ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - <img width="595" height="94" alt="h1" src="https://github.com/user-attachments/assets/ff0382aa-c622-4f6f-bb26-981637cf0245" />
        <img width="957" height="523" alt="h2" src="https://github.com/user-attachments/assets/4fdc714a-4a81-4274-9a37-51a0b8650ddb" />
        <img width="444" height="138" alt="h3" src="https://github.com/user-attachments/assets/432fa15a-d31b-4ef9-b646-47ec4e8dd3ff" />

        <img width="789" height="814" alt="h4" src="https://github.com/user-attachments/assets/27f30df5-6760-4b04-adbd-00133410e43d" />



    
- [ o]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        -target_scores = scores[name]
    student_total = sum(target_scores.values())
    student_avg = student_total / len(subjects)
           -키만 입력해서 원하는 점수만 쏙쏙 뽑아낸다.
          
- [ x]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
- [x ]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 
        - 애초에 회고를 작성하는곳이 없었고 아직 처음하는 부분이라 생각하기 쉽지않은 부분인것 같다.
        
- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        -  if name not in scores:
        print(f"{name} 학생의 성적을 찾을 수 없습니다.")
        return<--- 혹시나 이름입력이 잘못되었을때 오류를 사전에 방지해 입력실수를 사전에 방지하여 효율적인거 같았다. 


# 회고(참고 링크 및 코드 개선)
```
#  text = text.replace("","") <--(" ","  ") 공백이 있는 회문 판별시 공백제거 효과 추가
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```
