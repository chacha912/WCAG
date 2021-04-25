# 📑 WCAG (Web Content Accessibility Guidelines) 2.1

W3C 웹 콘텐츠 접근성 지침 표준 권고안은 **장애가 있는 사용자가 보다 쉽게 콘텐츠를 이용할 수 있도록 웹사이트/애플리케이션에서 충족해야 하는 기준을 정의** 합니다. 웹 서비스를 제작하는 사람들은 기획/디자인/개발 과정에서 WCAG 요구사항을 고려해야 합니다.WCAG 기준에 따라 웹사이트를 제작하면 장애를 가진 사람들 뿐 아니라 노화로 인해 능력이 감소된 노인의 접근성, 일반 사용자의 사용성 또한 향상시킬 수 있습니다.

## 🔎 WCAG 버전

| 버전 | 출간 | 특징                                                                                                                                                      |                링크                 |
| :--: | :--: | :-------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------: |
| 1.0  | 1999 | - 14개의 가이드라인을 [우선순위에 따라 1~3점](#priority)으로 구분하여 평가<br> - 접근성 가이드라인이 생겼다는 점에서 의미있음                             | [📃](https://www.w3.org/TR/WCAG10/) |
| 2.0  | 2008 | - 가이드라인 1.0의 준수사항을 모두 통합하면서 [4가지 원칙](#principle)으로 구조가 개편됨<br>- 12개 가이드라인을 제시                                      | [📃](https://www.w3.org/TR/WCAG20/) |
| 2.1  | 2018 | - 2.0 버전을 확장하여 모바일 장치 사용자, **저시력/인지/학습장애** 를 가진 사람들을 위해 요구사항 개선<br>- 17개의 새로운 성공기준(Success Criteria) 추가 | [📃](https://www.w3.org/TR/WCAG21/) |

## 🔎 WCAG 2.1 정리

WCAG 2.1 의 가이드라인을 하나씩 알아보고 관련 사례를 정리했습니다. 자세한 내용은 아래 링크를 통해 확인할 수 있습니다.

### 1. Perceivable (인지)

표는 추가 필요

<table>
<thead>
<tr>
<th>지침</th>
<th>링크</th>
<th>성공기준</th>
<th>내용</th>
<th>적합성수준</th>
<th>2.1추가</th>
<tr>
</thead>
<tr>
<td>1.1<br>Text Alternatives</td>
<td>📁</td>
<td>1.1.1</td>
<td>Non-text Content</td>
<tr>
<tr>
<td rowspan='28'>1.2<br>Time-based Media</td>
<td>1.2.1</td>
<td>Audio-only and Video-only (Prerecorded)</td>
<td>📁</td>
<tr>
<tr>
<td>1.2.2</td>
<td>Captions (Prerecorded)</td>
<td>📁</td>
<tr>
<tr>
<td>1.2.3</td>
<td>Audio Description or Media Alternative (Prerecorded)</td>
<td>📁</td>
<tr>
<tr>
<td>1.2.4</td>
<td>Captions (Live)</td>
<td>📁</td>
<tr>
<tr>
<td>1.2.5</td>
<td>Audio Description (Prerecorded)
</td>
<td>📁</td>
<tr>
<tr>
<td>1.2.6</td>
<td>Sign Language (Prerecorded)
</td>
<td>📁</td>
<tr>
<tr>
<td>1.2.7</td>
<td>Extended Audio Description (Prerecorded)</td>
<td>📁</td>
<tr>
<tr>
<td>1.2.8</td>
<td>Media Alternative (Prerecorded)</td>
<td>📁</td>
<tr>
<tr>
<td>1.2.9</td>
<td>Audio-only (Live)
</td>
<td>📁</td>
<tr>
</table>

<h2 id='priority'>🔎 WCAG Priority & Conformance</h2>

WCAG 1.0 버전은 우선순위를 기준으로 가이드라인을 제공하며, 우선순위 만족에 따라 적합 레벨을 결정했습니다. WCAG 2.0 버전은 웹접근성의 4가지 원칙을 기준으로 가이드라인을 제공하며, 각각의 가이드라인은 A, AA, AAA 수준(level)에 따른 성공기준(success criteria)을 가집니다. 따라서 적합성 수준은 성공기준에 따라 결정됩니다.
WCAG 2.0 에서는 하나의 가이드라인이 여러개의 성공기준을 가질 수 있습니다.
예시) 색상 대비가 4.5: 1을 만족하면 AA수준이고 7: 1을 만족하면 AAA수준입니다.

<details>
<summary>WCAG 1.0 우선순위(Priorities)</summary>

- 우선순위 1 (Priority 1)
  기본적인 요구사항으로 반드시 만족해야하는 기준입니다. 준수하지 않을 시 웹콘텐츠에 접근이 불가능합니다.
- 우선순위 2 (Priority 2)
  권장기준으로 준수하지 않을시 웹콘텐츠 접근에 어려움이 있습니다. 우선순위 2를 만족한다면 웹콘텐츠 접근 시 장벽을 제거할 수 있습니다.
- 우선순위 3 (Priority 3)
웹개발 시 해당 기준을 고려해볼 수 있습니다. 이 기준을 만족한다면 웹 콘텐츠 접근성을 향상시킬 수 있습니다.
</details>
<details>
<summary>WCAG 1.0 적합성 수준(Conformance)</summary>

|   수준   | 설명                              |
| :------: | :-------------------------------- |
|    A     | 우선순위 1을 모두 만족합니다.     |
| Double-A | 우선순위 1과 2를 모두 만족합니다. |
| Triple-A | 우선순위 1,2,3을 모두 만족합니다. |

</details>
<details>
<summary>WCAG 2.0 적합성 수준(Conformance)</summary>

| 수준 | 설명                                                                         |
| :--: | :--------------------------------------------------------------------------- |
|  A   | 최소 수준의 적합성(광범위한 접근성을 달성하지는 못함)                        |
|  AA  | 가장 일반적인 수준의 적합성(대부분의 법률 및 공식 요구 사항으로 준수를 권장) |
| AAA  | 어려운 수준의 적합성(매우 까다롭고, 구현에 많은 시간이 요구됨)               |

</details>
<br>

[📌 WCAG 1.0 과 WCAG 2.0 차이 ](https://www.w3.org/WAI/WCAG20/from10/diff.php)
[📌 WCAG 1.0 과 WCAG 2.0 의 우선순위 비교 ](https://www.w3.org/WAI/WCAG20/from10/comparison-priorities/)

<h2 id='principle'>🔎 WCAG의 4가지 원칙
</h2>
WCAG는 각 지침을 4가지 원칙의 범주로 분류하여 제공합니다.
`인식` 가능하고, `조작` 가능하며, `이해`할 수 있고, `견고`해야 합니다.

| 원칙                       | 설명                                                                    | 예시                                                              |
| :------------------------- | :---------------------------------------------------------------------- | :---------------------------------------------------------------- |
| 인식 <br/>`Perceivable`    | 모든 사용자는 서비스 콘텐츠를 인식할 수 있어야 합니다.                  | 시/청각 장애를 가진 사용자가 서비스를 인식하는데 문제가 없나요?   |
| 운용 <br/>`Operable`       | 모든 사용자는 서비스의 기능을 운용할 수 있어야 합니다.                  | 마우스 없이 서비스를 이용할 수 있고, 성공적으로 수행할 수 있나요? |
| 이해 <br/>`Understandable` | 모든 사용자가 서비스의 콘텐츠, 기능 사용법 등을 이해하기 쉬워야 합니다. | 명확하고 이해하기 쉬운 콘텐츠를 제공하고 있나요?                  |
| 견고 <br/>`Robust`         | 사용자가 이용하는 모든 기기 및 브라우저에게 접근, 사용 가능해야 합니다. | 특정 운영체제 또는 브라우저에서만 서비스를 이용할 수 있지 않나요? |

---

📚 참고자료

- [📌 a11y WCAG 2.1 깃북](https://a11y.gitbook.io/wcag/)
