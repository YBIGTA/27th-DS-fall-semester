# 27th DS Fall – OT 과제 -1: Transformer

> **요약**: 저장소를 클론한 뒤, 각 모듈의 **`#TODO`** 를 채우고 `main.ipynb`를 실행해 결과를 확인합니다. 동일한 파일 구조로 **새 브랜치**를 만들어 전체 파일을 푸시하면 제출 완료입니다. (브랜치명은 자유이나 **본인 이름 포함** 권장)

---

## 1) 시작하기

```bash
git clone https://github.com/YBIGTA/27th-DS-fall-semester.git
cd 27th-DS-fall-semester
```

> Jupyter 환경에서 `main.ipynb`를 실행할 수 있도록 Python 3.10+ 및 필요한 패키지를 준비해 주세요.

---

## 2) 과제 규칙
- **`#TODO` 채우기**: 각 모듈 파일에 있는 빈 로직을 완성합니다.
- **타입 힌트(typing) 수정 금지**: 모든 시그니처는 이미 타입이 지정되어 있으며, **타이핑을 바꾸지 않는 것**이 전체 모듈을 건드리지 않는 최선의 방법입니다.
- **“one line!” 항목**: 정말 **한 줄로** 작성합니다. 반환값이 필요하다면 **`return ...` 한 줄**로 끝내세요.
- **파일 구조 유지**: 레포의 **기존 디렉터리/파일 구조를 그대로** 유지합니다.
- **`main.ipynb` 실행**: 구현 확인은 노트북에서 수행합니다.

---

## 3) 제출 방법

1. 동일한 파일 구조로 **새 브랜치 생성**
   ```bash
   git checkout -b <your-name>/<short-topic>
   ```
   - 예시: `hyeongjin/transformer-todos`, `kim-hj/encoder-decoder`

2. 변경 사항 커밋 & 푸시
   ```bash
   git add -A
   git commit -m "Complete TODOs for transformer modules"
   git push origin <your-branch-name>
   ```

3. **제출 완료**
   - 새 브랜치로 **전체 파일을 푸시**하면 제출이 완료됩니다.
   - 브랜치명은 자유이나, **가급적 본인 이름을 포함**해 주세요.

---

## 4) 힌트 & 팁

- **구현 순서**: 실제 Transformer의 **동작 흐름 순서대로** 모듈을 채우면 수월합니다.
- **모듈 의존성**: 어떤 순서가 맞는지 애매하면 **모듈 간 import/의존성**을 먼저 살펴보세요.
- **기본 함수 적극 활용**: `torch`, `math`, `torch.nn`의 연산을 활용하세요  
  (예: `matmul`, `softmax`, `transpose`, `Dropout` …).
- **PyTorch 문서**
  - https://pytorch.org/docs/stable/generated/torch.nn.Module.html
  - https://pytorch.org/docs/stable/tensors.html

---

## 5) 체크리스트

- [ ] 모든 `#TODO`를 채웠다.
- [ ] **타입 힌트 수정 없음**을 확인했다.
- [ ] “one line!” 항목은 **정확히 한 줄**로 구현했다.
- [ ] `main.ipynb`를 실행해 동작을 확인했다.
- [ ] 새 브랜치에 **전체 파일**을 커밋/푸시했다.
- [ ] 브랜치명에 **본인 이름**을 포함했다(권장).
