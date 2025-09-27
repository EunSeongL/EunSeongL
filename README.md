<div align= "center">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=0453f1&height=180&text=EunSeong%20Lee's%20GitHub&animation=&fontColor=000000&fontSize=60" />
    </div>
    
## 🚀 MY Projects 🚀

| 프로젝트 (Project) | 설명 (Description) | 수행기관 (Organization) | 링크 (Links) |
|:---|:---|:---|:---|
| **Penalty Kick Game** <br> 📅(25.09.04 ~ 25.09.05) | 설명 | 대한상공회의소 | [Penalty Kick Game](https://github.com/EunSeongL/Ronaldo-Project) |
| **AXI4 Lite Protocol** <br> 📅(25.09.04 ~ 25.09.05) | 설명 | 대한상공회의소 | [AXI4 Lite Protocol](https://github.com/EunSeongL/AXI4-Lite-Protocol) |
| **RISC-V APB** <br> 📅(25.08.26 ~ 25.08.29) | - 설계한 RISC-V RV32I CPU에 ARM사의 AMBA APB Protocol Spec을 참고하여 **APB**를 설계, 통합후, 주변 장치를 연결<br> - **SystemVerilog Verification Testbench 구조**를 통해 DUT에 대한 검증<br> - **C -> 어셈블리어 -> 머신코드**로 변환 후 머신코드를 ROM에 넣어 정상적으로 동작하는 것을 확인 | 대한상공회의소 | [RISC-V AMBA APB](https://github.com/EunSeongL/RISCV-AMBA-APB) |
| **CPU Design** <br> 📅(25.08.14 ~ 25.08.29) | - RISC-V 명령어 세트 아키텍처를 기반으로 구현한 32비트 **(Single, Multi)-Cycle** CPU 설계<br> - CPU의 핵심 구성 요소인 **DataPath**와 **ControlUnit**을 System Verilog를 사용하여 설계<br> - Vivado EDA tool을 활용하여 RTL 코드를 합성 후 시뮬레이션을 통해 **모든 명령어 타입 검증**.<br> - C언어 코드를 머신코드로 변환하여 실행함으로써, 소프트웨어와 하드웨어 간의 동작방식을 이해 | 대한상공회의소 | [CPU Design](https://github.com/EunSeongL/CPU-Design) |
| **DSP FFT Design** <br> 📅(25.08.14 ~ 25.08.29) | - **MATLAB**을 활용해 **Radix-2 FFT**의 Butterfly 구조 이해<br> - **Floating-Point**와 **Fixed-Point** 차이 분석.<br> - **BFP**와 **CBFP** 적용 효과를 확인하여 정밀도와 연산 효율 비교.<br> - **소프트웨어 모델링** 기반 **하드웨어 모듈** 설계.<br> - Synopsys EDA Tool을 이용해 RTL 및 Gate Level **합성 결과**를 바탕으로 면적과 타이밍 특성을 분석<br> - Vivado를 활용해 FPGA 검증과 Bitstream생성.<br> - 알고리즘부터 **RTL 설계**, **NetList**생성, **FPGA Bitstream**생성까지 전반적인 **Front-End** 과정 학습.<br> | 대한상공회의소 | [FFT Design](https://github.com/EunSeongL/FFT-Design) |
| **AI NUTRI VIEW** <br> 📅(25.07.01 ~ 25.07.10) | - **Ai Nutri View**는 딥러닝과 LLM을 활용해 웹캠으로 사용자의 나이와 성별을 분석 후 맞춤형 영양제를 추천하는 헬스케어 시스템.<br> - **Xilinx FPGA DPU** 환경에 딥러닝 모델을 최적화하여 CPU 대비 **36배 빠른 추론 속도** 달성.<br> - **전력 효율**을 구현하며 실시간 **AI 가이드** 가능성을 검증. | 대한상공회의소 | [AI NUTRI VIEW](https://github.com/EunSeongL/AI_Age_Body_Tablet) |
| **Digital Clock** <br> 📅(25.05.20 ~ 25.06.02) | - **Basys3 FPGA 보드**를 이용해 **디지털 시계(WATCH & STOPWATCH)**, **UART 통신**, **초음파 센서(HC-SR04)**, **온습도 센서(DHT11)** 를 통합.<br> - **각 모듈을 블록화**하여 Top Module에서 통합 동작하도록 설계·검증 | 대한상공회의소 | [Digital Clock](https://github.com/EunSeongL/Digital-Clock) |
| **탄환지옥-생존의무대** <br> 📅(25.04.25 ~ 25.05.02) | - **ARM Cortex-M3** 기반의 마이크로컨트롤러에서 게임 로직 구현 및 **레지스터 기반 하드웨어 제어**<br> - 타이머, GPIO, PWM, 인터럽트 등 **데이터시트를 참고하여 필요한 레지스터 비트를 직접 활성화**하고 활용<br> - 임베디드 환경에서 실시간 제어와 인터럽트 기반 프로그래밍 이해 | 대한상공회의소 | [Avoid Bullets](https://github.com/EunSeongL/Avoid-Bullets) |
| **샘플링 기법 기반 확장 칼만 필터(EKF)를 이용한 배터리 SOC 추정 알고리즘의 하드웨어 구현** <br> 📅(24.02 ~ 24.06) | - 전기차 배터리 **안전 문제** 해결을 위해 **하드웨어 기반 EKF**를 적용하여 **SOC 추정**을 수행, **소프트웨어 부담**과 **시스템 과부하**를 줄임.<br> - **Samsung INR21700-50E 배터리** 대상 **SOC 예측·칼만 이득 계산·업데이트**를 수행하며, 충·방전 상태에 따라 **샘플링 간격**을 조절.<br> - **고정소수점 연산**과 **truncation**으로 **RMSE 최소화**, **ALU 병렬 처리**로 **연산 속도 향상** 및 **면적 절감**.<br> - **Verilog RTL 구현** 후 **소프트웨어와 비교 검증** 결과 **0.001417% 오차**, **FPGA(DE2-115) 합성**으로 실제 **SOC 추정 성능** 확인. | 상명대학교 | [Battery SOC EKF](https://github.com/EunSeongL/Battery-SOC-EKF) | <br>
| **FIR Filter Design** <br> 📅(24.06.17 ~ 24.06.23) | 설명 | 상명대학교 | [FIR Filter Design](https://github.com/EunSeongL/FIR-Filter-Design) |

## 🚀 Tech Stack 🚀

<table>
  <tr>
    <td align="center" width="180"><strong>Languages</strong></td>
    <td>
      <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white"/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/Verilog-8E2285?style=for-the-badge&logo=verilog&logoColor=white"/>
      <img src="https://img.shields.io/badge/SystemVerilog-8E2285?style=for-the-badge&logo=systemverilog&logoColor=white"/>
      <img src="https://img.shields.io/badge/matlab-3776AB?style=for-the-badge&logo=matlab&logoColor=white"/>  
      <img src="https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center"><strong>MCU</strong></td>
    <td>
      <img src="https://img.shields.io/badge/ATmega128-E34F26?style=for-the-badge&logo=microchip-technology&logoColor=white"/>
      <img src="https://img.shields.io/badge/STM32%20Cortex--M3-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white" alt="STM32 Cortex-M3" />
    </td>
  </tr>
  <tr>
    <td align="center"><strong>AP</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberry-pi&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center"><strong>IDE</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white"/>
      <img src="https://img.shields.io/badge/Visual%20Studio-5C2D91?style=for-the-badge&logo=visual-studio&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center"><strong>EDA Tools</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Vivado-00A652?style=for-the-badge&logo=xilinx&logoColor=white"/>
      <img src="https://img.shields.io/badge/Vitis-FA2E2E?style=for-the-badge&logo=xilinx&logoColor=white"/>
      <img src="https://img.shields.io/badge/STM32CubeIDE-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white"/>
      <img src="https://img.shields.io/badge/VCS-8E2285?style=for-the-badge&logo=synopsys&logoColor=white"/>
      <img src="https://img.shields.io/badge/Verdi-22225B?style=for-the-badge&logo=synopsys&logoColor=white"/>
      <img src="https://img.shields.io/badge/Synopsys%20Custom%20Compiler-4B0082?style=for-the-badge&logo=synopsys&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center"><strong>Version Control</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center"><strong>Operating System</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
      <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white"/>
      <img src="https://img.shields.io/badge/CentOS-22225B?style=for-the-badge&logo=centos&logoColor=white"/>
      <img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center"><strong>Office</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white"/>
      <img src="https://img.shields.io/badge/Microsoft%20Word-2B579A?style=for-the-badge&logo=microsoft-word&logoColor=white"/>
      <img src="https://img.shields.io/badge/Microsoft%20PowerPoint-B7472A?style=for-the-badge&logo=microsoft-powerpoint&logoColor=white"/>
      <img src="https://img.shields.io/badge/Microsoft%20Office-D83B01?style=for-the-badge&logo=microsoft-office&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center"><strong>Frameworks, Platforms<br/>and Libraries</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Anaconda-44A833?style=for-the-badge&logo=anaconda&logoColor=white"/>
      <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>
      <img src="https://img.shields.io/badge/TensorFlow-B7472A?style=for-the-badge&logo=tensorflow&logoColor=white"/>
      <img src="https://img.shields.io/badge/Keras-4B0082?style=for-the-badge&logo=keras&logoColor=white"/>  
    </td>
  </tr>
</table>
<br>

<div style="text-align: left;">
  <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🧑‍💻 Contact me </h2>
  <div style="text-align: left;">
    <a href="mailto:dldmstjd07272@gmail.com">
      <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=Gmail&logoColor=white">
    </a>
    <a href="https://www.linkedin.com/in/은성-이-779088318/">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=LinkedIn&logoColor=white">
    </a>
  </div>
</div>

<div style="text-align: left;">
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🏅 Stats </h2>
    <div style="text-align: left;">
    <img src="https://github-readme-stats.vercel.app/api?username=EunSeongL&show_icons=true&custom_title=EunSeongL's%20Github%20Stats&bg_color=blue&title_color=black&text_color=black&icon_color=black" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=EunSeongL&layout=compact&bg_color=black&title_color=black&text_color=black" />
    </div>
</div>

<!--
**EunSeongL/EunSeongL** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
