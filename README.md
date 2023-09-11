# Developing-an-IoT-based-smart-wheelchair-that-automatically-adjusts-its-tilt-based-on-incline
##[캡스톤 디자인] 경사에 따라 자동으로 기울기를 조정하는 IoT 기반 스마트 휠체어 개발

##서론
휠체어 사용자들이 직면하는 주요 문제점들은 안전사고 발생률이 높고, 이동성이 제한되며, 자립성이 낮다는 것이다. 이러한 문제들은 사용자들의 생활 만족도를 저하시키며, 자신의 의사나 감정을 표현하는데 어려움을 겪게 한다. 또한, 사회적 차별이나 고립감을 경험하게 한다. 특히, 안전사고 발생률이 높은 이유는 넘어짐이나 충돌 등으로 인한 부상이 잦기 때문이다. 휠체어 사용자들은 도로나 건물 등의 접근성이 불편하고, 기울기나 장애물 등에 따라 이동하기 어렵다.
따라서, 본 연구에서는 이러한 문제점을 해결하고자 스마트 IoT 휠체어를 제안하였다. 스마트 IoT 휠체어는 사용자의 안전과 편의성을 증진시키며, 클라우드 컴퓨팅을 활용하여 다양한 환경에서도 원활하게 이동할 수 있도록 돕는다. 이 기술은 노약한 국가유공자나 장애인 등에게 유익하며, 사회적 책임과 공익을 실현하는데 기여할 것이다.

##관련 연구
스마트 휠체어에 대한 연구는 세계 각지에서 진행되고 있다. 가령, 펌웨어와 소프트웨어가 통합된 "UPnRIDE" 휠체어는 사용자가 세로로 안정적으로 서있을 수 있게 해주는 기술을 탑재하였다. 또한, "WHILL Model Ci"는 다양한 지형에 적응할 수 있도록 디자인되었으며, 스마트폰 앱을 통해 편리하게 제어할 수 있다. 또한 "Quantum Rehab's iLevel"는 사용자가 움직이면서도 시트를 12인치까지 높일 수 있게 해주는 기능을 가지고 있다. 이와 같은 기존의 스마트 휠체어들은 각각 독특한 기능들을 제공하고 있지만, 경사로나 불균형한 표면에서의 안정성과 이동성을 보장하는 데는 한계가 있다.
본 연구에서는 이러한 기존 연구를 바탕으로 하되, 사용자의 이동 경로와 환경에 따라 휠체어의 기울기를 자동으로 조정하는 기능을 추가하였다. 해당 휠체어는 기존의 스마트 휠체어와 비교했을 때, 앞바퀴의 높이조절을 통해 경사로에서 기울기를 조정하는 차별성을 갖고 있다. 이를 통해 경사로에서의 이동이 빈번한 사용자들에게는 특히 유용하며, 안정성과 이동 편의성을 더욱 높일 수 있다.

##스마트 IoT 휠체어의 주요 기능과 기대효과
### 주요 기능
1. 자동 기울기 조정 : 가속도 센서와 기울기 센서를 사용하여 휠체어의 현재 기울기를 측정하고, 이를 통해 휠체어가 안전하게 이동할 수 있는 기울기를 자동으로 조정한다.
2. 넘어짐 감지 및 자동 신고 : 가속도 센서와 기울기 센서를 통해 휠체어의 기울기가 너무 크거나 불안정해질 경우 이를 감지하고, 자동으로 신고하는 기능을 가지고 있다.
3. 장애물 감지 : 초음파 거리센서를 통해 장애물을 인식하고 거리를 측정 후, 위급상황시 긴급제동하는 충돌 방지 기능.
4. 사용자 착석 감지 : 압력센서와 안전벨트 체결 여부를 확인해 사용자의 착석을 감지하는 기능.
5. 오토 라이트 : 조도센서 감지를 통해 자동으로 전방 라이트를 점등시켜 어두운 환경에서 사용자의 위치를 알리는 기능.
6. 과속 감지 : 자기 센서를 통해 바퀴에 장착된 자석이 한바퀴 도는 타이밍을 계산해 현재 속도가 임계속도를 넘으면 긴급 정지하는 기능.

###기대효과
스마트 IoT 휠체어의 개발은 사용자의 안전과 편의성을 개선하고 일상생활의 질을 높이는데 기여할 것으로 예상된다. 센서를 통해 주변 환경을 인식하고, 충돌을 방지하거나 긴급 상황에서 정지하는 기능을 통해 사용자의 안전을 보장한다. 또한, 클라우드 서버와 연동하여 사용자의 위치를 실시간으로 모니터링하고, 필요한 경우 즉시 구조 요청이 가능하다. 이러한 기능은 특히 독거노인이나 독립적으로 생활하는 장애인들에게 큰 도움이 될 것이다. 그러므로 스마트 IoT 휠체어의 개발은 단순히 이동의 편의성을 넘어 사용자의 안전과 생활 품질을 개선하는 중요한 역할을 할 것으로 기대된다.

##개발 환경
본 연구에서는 아두이노 IoT 클라우드와 아두이노 IDE를 사용하여 개발 환경을 구축하였다.

##결론
본 논문에서는 휠체어 사용자의 안전과 이동성을 증진시키는 IoT 기반 스마트 휠체어의 개발에 대해 소개하였다. 특히, 경사로에 따라 자동으로 기울기가 조정되는 기능을 중점적으로 개발하였으며, 이는 사용자의 안전을 높이고 이동의 편의성을 증가시킨다. 또한, 장애물 감지, 과속 감지, 착석 감지 등 다양한 안전 기능을 통해 휠체어 사용자의 생활을 보다 안전하고 편리하게 만드는 것이 목표이다. 이러한 기술의 발전은 휠체어 사용자뿐만 아니라 모든 이동 보조 도구 사용자에게 도움이 될 것으로 기대된다.

##참고 문헌 (참고자료)
1. Al Shabibi, M. A. K & Kesavan, S. M., "IoT Based Smart Wheelchair for Disabled People", 2021 International Conference on System, Computation, Automation and Networking (ICSCAN), pp.1~6, July,  2021
2. Sakakibara, B. M., Miller, W. C., Eng, J. J., Routhier, F.  & Backman, C. L., "Health, Personal, and Environmental Predictors of Wheelchair-Use Confidence in Adult Wheelchair Users", Physical Therapy, Vol. 95, pp.1365~1373, October, 2015.
3. UPnRIDE Robotics, "UPnRIDE - Mobility Reimagined," UPnRIDE Robotics, [Online]. Available: https://upnride.com/.
4. WHILL, "Personal Electric Vehicles," WHILL, [Online]. Available: https://whill.inc/us/.
5. Quantum Rehab, "iLevel Wheelchairs," Quantum Rehab, [Online]. Available: https://www.quantumrehab.com/ilevel-power-chairs/.
