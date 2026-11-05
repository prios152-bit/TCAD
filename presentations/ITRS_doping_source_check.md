# ITRS 2001 도핑 설명 원문 검증

검토 범위: 업로드된 2001FEP.pdf 및 2001PIDS.pdf. 인쇄 쪽수와 PDF 쪽수는 4쪽 차이.

| 첨부 설명의 주장 | 판정 / 원문 근거 |
|---|---|
| FEP에는 Npoly 관련 도핑 수치가 없다 | 수정 필요. Table 51a 인쇄 p.20(PDF24)에 Active poly doping for 25% depletion allowance = 9.2e19 cm^-3(2001 MPU/ASIC). SDE 변수명 Npoly는 아님. |
| 활성 농도 상한은 1e20~3e20이다 | 두 PDF에서 일반적 절대 상한의 근거 미확인. FEP p.3(PDF7)은 solid solubility보다 큰 활성 농도를 과제로 명시함. |
| 2e20 수치가 있다 | 있음. FEP p.27(PDF31)의 p+ polysilicon 활성 농도 약 2e20 달성 과제. Nsd 또는 n+ NMOS gate의 보편적 설정값이 아님. |
| Nsd = 2e20~3e20이 FEP 규격이다 | 근거 미확인. S/D 고농도·활성화·접합·저항은 논의하나 2001 LOP NMOS의 단일 Nsd 지정값은 찾지 못함. |
| Extension 및 Deep S/D 최대 면저항이 각각 규정됨 | 부분 지지. Table 51a의 400 ohm/sq는 PMOS extension. Contact silicide sheet Rs 4.2 ohm/sq와 contact rho_c 4.1e-7 ohm cm^2는 서로 다른 물리량이며 deep semiconductor S/D 면저항으로 바꾸면 안 됨. |
| 저항 목표는 반드시 Nsd >=1e20을 요구한다 | 일반화 근거 미확인. 프로파일, 활성 농도, 이동도, 접합 깊이, contact와 공동 최적화 필요. |
| Poly depletion을 없애 전압이 전부 산화막에 걸리게 해야 한다 | 수정 필요. FEP p.28(PDF32)는 EOT의 25% 공핍 할당을 허용. p.20의 도핑값도 해당 기준에 연동됨. |

FEP p.22 [H][Q]: extension 저항, lateral abruptness, contact 비저항을 공동 최적화해야 함. [Q] 값은 이론적 최대이며 실제 설계에 그대로 사용할 수 없다고 명시.

전기적으로 활성화된 도핑, 주입/총 화학 도핑, SDE에 입력하는 농도는 구분해야 함. Npoly/Nsd sweep값은 원문 규격이 아니라 모델링 가정으로 기록하고 검증.

PPT 7쪽에 원문 캡처와 요약을 추가했고 기존 소자 구조 부록은 8쪽으로 이동. 기존 본편 6장은 유지. 새 검증 슬라이드까지 자세히 발표하면 약 1분 추가되므로 5분 발표에서는 질의응답용으로 활용 가능.
