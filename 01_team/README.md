# 📑 WCAG (Web Content Accessibility Guidelines) 2.1

W3C 웹 콘텐츠 접근성 지침 표준 권고안은 **장애가 있는 사용자가 보다 쉽게 콘텐츠를 이용할 수 있도록 웹사이트/애플리케이션에서 충족해야 하는 기준을 정의** 합니다. 웹 서비스를 제작하는 사람들은 기획/디자인/개발 과정에서 WCAG 요구사항을 고려해야 합니다. WCAG 기준에 따라 웹사이트를 제작하면 장애를 가진 사람들 뿐 아니라 노화로 인해 능력이 감소된 노인의 접근성, 일반 사용자의 사용성 또한 향상시킬 수 있습니다.

## 🔎 WCAG 버전

| 버전 | 출간 | 특징                                                                                                                                                      |                링크                 |
| :--: | :--: | :-------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------: |
| 1.0  | 1999 | - 14개의 가이드라인을 [우선순위에 따라 1~3점](#priority)으로 구분하여 평가<br> - 접근성 가이드라인이 생겼다는 점에서 의미있음                             | [📃](https://www.w3.org/TR/WCAG10/) |
| 2.0  | 2008 | - 가이드라인 1.0의 준수사항을 모두 통합하면서 [4가지 원칙](#principle)으로 구조가 개편됨<br>- 12개 가이드라인을 제시                                      | [📃](https://www.w3.org/TR/WCAG20/) |
| 2.1  | 2018 | - 2.0 버전을 확장하여 **모바일 장치 사용자, 저시력/인지/학습장애** 를 가진 사람들을 위해 요구사항 개선<br>- 17개의 새로운 성공기준(Success Criteria) 추가 | [📃](https://www.w3.org/TR/WCAG21/) |

## 🔎 WCAG 2.1 정리

WCAG 2.1 의 가이드라인(지침)을 하나씩 알아보고 관련 사례를 정리했습니다. 각 지침에 대한 자세한 내용은 아래 표의 링크를 통해 확인할 수 있습니다.

<details>
<summary><strong>1. 인식 (Perceivable) <a href="./01-perceivable-kjw/">📁</a></strong></summary>

<table>
      <thead>
        <tr>
          <th>지침</th>
          <th>링크</th>
          <th>성공기준</th>
          <th>내용</th>
          <th>적합성수준</th>
          <th>2.1추가</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>1.1<br />대체 텍스트<br />(Text Alternatives)</td>
          <td><a href="./01-perceivable-kjw/01-text-alternatives">📁</a></td>
          <td>1.1.1</td>
          <td>Non-text Content</td>
          <td>A</td>
          <td></td>
        </tr>
      </tbody>
      <tbody>
        <tr>
          <td rowspan="18">1.2<br />시간기반 미디어<br />(Time-based Media)</td>
          <td rowspan="18"><a href="./01-perceivable-kjw/02-time-based-media">📁</a></td>
          <td>1.2.1</td>
          <td>Audio-only and Video-only (Prerecorded)</td>
          <td>A</td>
          <td></td>
        </tr>
        <tr>
          <td>1.2.2</td>
          <td>Captions (Prerecorded)</td>
          <td>A</td>
          <td></td>
        </tr>
        <tr>
          <td>1.2.3</td>
          <td>Audio Description or Media Alternative (Prerecorded)</td>
          <td>A</td>
          <td></td>
        </tr>
        <tr>
          <td>1.2.4</td>
          <td>Captions (Live)</td>
          <td>AA</td>
          <td></td>
        </tr>
        <tr>
          <td>1.2.5</td>
          <td>Audio Description (Prerecorded)</td>
          <td>AA</td>
          <td></td>
        </tr>
        <tr>
          <td>1.2.6</td>
          <td>Sign Language (Prerecorded)</td>
          <td>AAA</td>
          <td></td>
        </tr>
        <tr>
          <td>1.2.7</td>
          <td>Extended Audio Description (Prerecorded)</td>
          <td>AAA</td>
          <td></td>
        </tr>
        <tr>
          <td>1.2.8</td>
          <td>Media Alternative (Prerecorded)</td>
          <td>AAA</td>
          <td></td>
        </tr>
        <tr>
          <td>1.2.9</td>
          <td>Audio-only (Live)</td>
          <td>AAA</td>
          <td></td>
        </tr>
      </tbody>
      <tbody>
        <tr>
          <td rowspan="12">1.3<br />적응 가능<br />(Adaptable)</td>
          <td rowspan="12"><a href="./01-perceivable-kjw/03-adaptable">📁</a></td>
          <td>1.3.1</td>
          <td>Info and Relationships</td>
          <td>A</td>
          <td></td>
        </tr>
        <tr>
          <td>1.3.2</td>
          <td>Meaningful Sequence</td>
          <td>A</td>
          <td></td>
        </tr>
        <tr>
          <td>1.3.3</td>
          <td>Sensory Characteristics</td>
          <td>A</td>
          <td></td>
        </tr>
        <tr>
          <td>1.3.4</td>
          <td>Orientation</td>
          <td>AA</td>
          <td>New✨<br>모바일</td>
        </tr>
        <tr>
          <td>1.3.5</td>
          <td>Identify Input Purpose</td>
          <td>AA</td>
          <td>New✨<br>인지</td>
        </tr>
        <tr>
          <td>1.3.6</td>
          <td>Identify Purpose</td>
          <td>AAA</td>
          <td>New✨<br>인지</td>
        </tr>
      </tbody>
      <tbody>
        <tr>
          <td rowspan="26">1.4<br />식별 가능<br />(Distinguishable)</td>
          <td rowspan="26"><a href="./01-perceivable-kjw/04-distinguishable">📁</a></td>
          <td>1.4.1</td>
          <td>Use of Color</td>
          <td>A</td>
          <td></td>
        </tr>
        <tr>
          <td>1.4.2</td>
          <td>Audio Control</td>
          <td>A</td>
          <td></td>
        </tr>
        <tr>
          <td>1.4.3</td>
          <td>Contrast (Minimum)</td>
          <td>AA</td>
          <td></td>
        </tr>
        <tr>
          <td>1.4.4</td>
          <td>Resize text</td>
          <td>AA</td>
          <td></td>
        </tr>
        <tr>
          <td>1.4.5</td>
          <td>Images of Text</td>
          <td>AA</td>
          <td></td>
        </tr>
        <tr>
          <td>1.4.6</td>
          <td>Contrast (Enhanced)</td>
          <td>AAA</td>
          <td></td>
        </tr>
        <tr>
          <td>1.4.7</td>
          <td>Low or No Background Audio</td>
          <td>AAA</td>
          <td></td>
        </tr>
        <tr>
          <td>1.4.8</td>
          <td>Visual Presentation</td>
          <td>AAA</td>
          <td></td>
        </tr>
        <tr>
          <td>1.4.9</td>
          <td>Images of Text (No Exception)</td>
          <td>AAA</td>
          <td></td>
        </tr>
        <tr>
          <td>1.4.10</td>
          <td>Reflow</td>
          <td>AA</td>
          <td>New✨<br>저시력</td>
        </tr>
        <tr>
          <td>1.4.11</td>
          <td>Non-text Contrast</td>
          <td>AA</td>
          <td>New✨<br>저시력</td>
        </tr>
        <tr>
          <td>1.4.12</td>
          <td>Text Spacing</td>
          <td>AA</td>
          <td>New✨<br>저시력</td>
        </tr>
        <tr>
          <td>1.4.13</td>
          <td>Content on Hover or Focus</td>
          <td>AA</td>
          <td>New✨<br>저시력</td>
        </tr>
      </tbody>
    </table>

</details>
<details>
<summary><strong>2. 운용 (Operable) <a href="./02-operable-cyr">📁</a></strong></summary>

<table>
      <thead>
        <tr>
          <th>지침</th>
          <th>링크</th>
          <th>성공기준</th>
          <th>내용</th>
          <th>적합성수준</th>
          <th>2.1추가</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td rowspan="8">2.1<br />키보드 접근성<br />(Keyboard Accessible)</td>
          <td rowspan="8"><a href="./02-operable-cyr/01-keyboard-accessible">📁</a></td>
          <td>2.1.1</td>
          <td>Keyboard</td>
          <td>A</td>
          <td></td>
        </tr>
        <tr>
          <td>2.1.2</td>
          <td>No Keyboard Trap</td>
          <td>A</td>
          <td></td>
        </tr>
        <tr>
          <td>2.1.3</td>
          <td>Keyboard (No Exception)</td>
          <td>AAA</td>
          <td></td>
        </tr>
        <tr>
          <td>2.1.4</td>
          <td>Character Key Shortcuts</td>
          <td>A</td>
          <td>New✨<br>모바일</td>
        </tr>
      </tbody>
      <tbody>
        <tr>
          <td rowspan="12">2.2<br />충분한 시간<br />(Enough Time)</td>
          <td rowspan="12"><a href="./02-operable-cyr/02-enough-time">📁</a></td>
          <td>2.2.1</td>
          <td>Timing Adjustable</td>
          <td>A</td>
          <td></td>
        </tr>
        <tr>
          <td>2.2.2</td>
          <td>Pause, Stop, Hide</td>
          <td>A</td>
          <td></td>
        </tr>
        <tr>
          <td>2.2.3</td>
          <td>No Timing</td>
          <td>AAA</td>
          <td></td>
        </tr>
        <tr>
          <td>2.2.4</td>
          <td>Interruptions</td>
          <td>AAA</td>
          <td></td>
        </tr>
        <tr>
          <td>2.2.5</td>
          <td>Re-authenticating</td>
          <td>AAA</td>
          <td></td>
        </tr>
        <tr>
          <td>2.2.6</td>
          <td>Timeouts</td>
          <td>AAA</td>
          <td>New✨<br>인지</td>
        </tr>
      </tbody>
      <tbody>
        <tr>
          <td rowspan="6">2.3<br />발작 및 신체적 반응<br />(Seizures and Physical Reactions)</td>
          <td rowspan="6"><a href="./02-operable-cyr/03-seizures-and-physical-reactions">📁</a></td>
          <td>2.3.1</td>
          <td>Three Flashes or Below Threshold</td>
          <td>A</td>
          <td></td>
        </tr>
        <tr>
          <td>2.3.2</td>
          <td>Three Flashes</td>
          <td>AAA</td>
          <td></td>
        </tr>
        <tr>
          <td>2.3.3</td>
          <td>Animation from Interactions</td>
          <td>AAA</td>
          <td>New✨<br>인지</td>
        </tr>
      </tbody>
      <tbody>
        <tr>
          <td rowspan="20">2.4<br />내비게이션 기능<br />(Navigable)</td>
          <td rowspan="20"><a href="./02-operable-cyr/04-navigable">📁</a></td>
          <td>2.4.1</td>
          <td>Bypass Blocks</td>
          <td>A</td>
          <td></td>
        </tr>
        <tr>
          <td>2.4.2</td>
          <td>Page Titled</td>
          <td>A</td>
          <td></td>
        </tr>
        <tr>
          <td>2.4.3</td>
          <td>Focus Order</td>
          <td>A</td>
          <td></td>
        </tr>
        <tr>
          <td>2.4.4</td>
          <td>Link Purpose (In Context)</td>
          <td>A</td>
          <td></td>
        </tr>
        <tr>
          <td>2.4.5</td>
          <td>Multiple Ways</td>
          <td>AA</td>
          <td></td>
        </tr>
        <tr>
          <td>2.4.6</td>
          <td>Headings and Labels</td>
          <td>AA</td>
          <td></td>
        </tr>
        <tr>
          <td>2.4.7</td>
          <td>Focus Visible</td>
          <td>AA</td>
          <td></td>
        </tr>
        <tr>
          <td>2.4.8</td>
          <td>Location</td>
          <td>AAA</td>
          <td></td>
        </tr>
        <tr>
          <td>2.4.9</td>
          <td>Link Purpose (Link Only)</td>
          <td>AAA</td>
          <td></td>
        </tr>
        <tr>
          <td>2.4.10</td>
          <td>Section Headings</td>
          <td>AAA</td>
          <td></td>
        </tr>
      </tbody>
      <tbody>
        <tr>
          <td rowspan="12">2.5<br />입력 방식<br />(Input Modalities)</td>
          <td rowspan="12"><a href="./02-operable-cyr/05-input-modalities">📁</a></td>
          <td>2.5.1</td>
          <td>Pointer Gestures</td>
          <td>A</td>
          <td>New✨<br>모바일</td>
        </tr>
        <tr>
          <td>2.5.2</td>
          <td>Pointer Cancellation</td>
          <td>A</td>
          <td>New✨<br>모바일</td>
        </tr>
        <tr>
          <td>2.5.3</td>
          <td>Label in Name</td>
          <td>A</td>
          <td>New✨<br>모바일</td>
        </tr>
        <tr>
          <td>2.5.4</td>
          <td>Motion Actuation</td>
          <td>A</td>
          <td>New✨<br>모바일</td>
        </tr>
        <tr>
          <td>2.5.5</td>
          <td>Target Size</td>
          <td>AAA</td>
          <td>New✨<br>모바일</td>
        </tr>
        <tr>
          <td>2.5.6</td>
          <td>Concurrent Input Mechanisms</td>
          <td>AAA</td>
          <td>New✨<br>모바일</td>
        </tr>
      </tbody>
    </table>

</details>

<details>
<summary><strong>3. 이해 (Understandable) <a href="./03-readable-jjh/">📁</a></strong></summary>

<table>
      <thead>
        <tr>
          <th>지침</th>
          <th>링크</th>
          <th>성공기준</th>
          <th>내용</th>
          <th>적합성수준</th>
          <th>2.1추가</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td rowspan="12">3.1<br />가독성<br />(Readable)</td>
          <td rowspan="12"><a href="./03-readable-jjh/01-readable">📁</a></td>
          <td>3.1.1</td>
          <td>Language of Page</td>
          <td>A</td>
          <td></td>
        </tr>
        <tr>
          <td>3.1.2</td>
          <td>Language of Parts</td>
          <td>AA</td>
          <td></td>
        </tr>
        <tr>
          <td>3.1.3</td>
          <td>Unusual Words</td>
          <td>AAA</td>
          <td></td>
        </tr>
        <tr>
          <td>3.1.4</td>
          <td>Abbreviations</td>
          <td>AAA</td>
          <td></td>
        </tr>
        <tr>
          <td>3.1.5</td>
          <td>Reading Level</td>
          <td>AAA</td>
          <td></td>
        </tr>
        <tr>
          <td>3.1.6</td>
          <td>Pronunciation</td>
          <td>AAA</td>
          <td></td>
        </tr>
      </tbody>
      <tbody>
        <tr>
          <td rowspan="10">3.2<br />예측 가능성<br />(Predictable)</td>
          <td rowspan="10"><a href="./03-readable-jjh/02-predictable">📁</a></td>
          <td>3.2.1</td>
          <td>On Focus</td>
          <td>A</td>
          <td></td>
        </tr>
        <tr>
          <td>3.2.2</td>
          <td>On Input</td>
          <td>A</td>
          <td></td>
        </tr>
        <tr>
          <td>3.2.3</td>
          <td>Consistent Navigation</td>
          <td>AA</td>
          <td></td>
        </tr>
        <tr>
          <td>3.2.4</td>
          <td>Consistent Identification</td>
          <td>AA</td>
          <td></td>
        </tr>
        <tr>
          <td>3.2.5</td>
          <td>Change on Request</td>
          <td>AAA</td>
          <td></td>
        </tr>
      </tbody>
      <tbody>
        <tr>
          <td rowspan="12">3.3<br />입력 지원<br />(Input Assistance)</td>
          <td rowspan="12"><a href="./03-readable-jjh/03-input-assistance">📁</a></td>
          <td>3.3.1</td>
          <td>Error Identification</td>
          <td>A</td>
          <td></td>
        </tr>
        <tr>
          <td>3.3.2</td>
          <td>Labels or Instructions</td>
          <td>A</td>
          <td></td>
        </tr>
        <tr>
          <td>3.3.3</td>
          <td>Error Suggestion</td>
          <td>AA</td>
          <td></td>
        </tr>
        <tr>
          <td>3.3.4</td>
          <td>Error Prevention (Legal, Financial, Data)</td>
          <td>AA</td>
          <td></td>
        </tr>
        <tr>
          <td>3.3.5</td>
          <td>Help</td>
          <td>AAA</td>
          <td></td>
        </tr>
        <tr>
          <td>3.3.6</td>
          <td>Error Prevention (All)</td>
          <td>AAA</td>
          <td></td>
        </tr>
      </tbody>
    </table>
</details>

<details>
<summary><strong>4. 견고 (Robust) <a href="./04-robust-jjh/">📁</a></strong></summary>

<table>
      <thead>
        <tr>
          <th>지침</th>
          <th>링크</th>
          <th>성공기준</th>
          <th>내용</th>
          <th>적합성수준</th>
          <th>2.1추가</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td rowspan="6">4.1<br />호환성<br />(Compatible)</td>
          <td rowspan="6"><a href="./04-robust-jjh/01-compatible">📁</a></td>
          <td>4.1.1</td>
          <td>Parsing</td>
          <td>A</td>
          <td></td>
        </tr>
        <tr>
          <td>4.1.2</td>
          <td>Name, Role, Value</td>
          <td>A</td>
          <td></td>
        </tr>
        <tr>
          <td>4.1.3</td>
          <td>Status Messages</td>
          <td>AA</td>
          <td>New✨<br>저시력</td>
        </tr>
        <tr>
      </tbody>
    </table>
</details>

<h2 id='priority'>🔎 WCAG 적합성 수준 (Conformance levels)</h2>

WCAG 1.0 버전은 **우선순위** 를 기준으로 가이드라인을 제공하며, 우선순위 만족에 따라 적합성 수준이 결정됐습니다.

#### WCAG 1.0 우선순위(Priorities)

|        우선순위         | 설명                                                                                                                                 |
| :---------------------: | :----------------------------------------------------------------------------------------------------------------------------------- |
| 우선순위 1 (Priority 1) | 기본적인 요구사항으로 반드시 만족해야하는 기준입니다. <br>준수하지 않을 시 웹콘텐츠에 접근이 불가능합니다.                           |
| 우선순위 2 (Priority 2) | 권장기준으로 준수하지 않을시 웹콘텐츠 접근에 어려움이 있습니다. <br>이 기준을 만족한다면 웹콘텐츠 접근 시 장벽을 제거할 수 있습니다. |
| 우선순위 3 (Priority 3) | 웹개발 시 해당 기준을 고려해볼 수 있습니다. <br>이 기준을 만족한다면 웹 콘텐츠 접근성을 향상시킬 수 있습니다.                        |

#### WCAG 1.0 적합성 수준

|   수준   | 설명                              |
| :------: | :-------------------------------- |
|    A     | 우선순위 1을 모두 만족합니다.     |
| Double-A | 우선순위 1과 2를 모두 만족합니다. |
| Triple-A | 우선순위 1,2,3을 모두 만족합니다. |

<br>

WCAG 2.0 버전은 **웹접근성의 4가지 원칙** 을 기준으로 가이드라인을 제공하며, 각각의 가이드라인은 A, AA, AAA 적합성 수준에 따른 성공기준(success criteria)을 가집니다. 따라서 WCAG 2.0 버전 이상에서 적합성 수준은 **성공기준** 에 따라 결정됩니다.  
WCAG 2.0 에서는 하나의 가이드라인이 여러개의 성공기준을 가질 수 있습니다.  
예시) 성공기준 1.4.3과 1.4.6은 같은 `명도 대비` 를 다루고 있지만 다른 기준을 적용합니다.

|       성공기준       | 명도대비 | 적합성 수준 |
| :------------------: | :------: | :---------: |
| 1.4.3 명도대비(최소) | 4.5 : 1  |     AA      |
| 1.4.6 명도대비(향상) |  7 : 1   |     AAA     |

#### WCAG 2.0 적합성 수준

| 수준 | 설명                                                                         |
| :--: | :--------------------------------------------------------------------------- |
|  A   | 최소 수준의 적합성(광범위한 접근성을 달성하지는 못함)                        |
|  AA  | 가장 일반적인 수준의 적합성(대부분의 법률 및 공식 요구 사항으로 준수를 권장) |
| AAA  | 어려운 수준의 적합성(매우 까다롭고, 구현에 많은 시간이 요구됨)               |

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

- [a11y WCAG 2.1 gitbook](https://a11y.gitbook.io/wcag/)
- [Welcome, WCAG 2.1](https://knowbility.org/blog/2018/WCAG21-intro/)
