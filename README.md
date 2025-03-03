# 21-1 SWIC Report(Team C, 1st Prize): ESG Active Fund
**팀장**: 기획 총괄, 보고서 전반 작성
<br>
> Code: 본 Repository 참고, Developed by Dongjun Shin
>
> Report: [Active Fund 2021-1.pdf](https://drive.google.com/file/d/10oYCZ6YMAij1Ynd1_f9KZt_kAafKpdGs/view?usp=sharing)

<br>

# Python Stock Tool
------

Start : 2021.02.11~

------

## Project Plan & Purpose

금융 공학 쪽으로 공부하면서 사용한 코드들을 항목&라이브러리 별로 정리

------

## Book

[파이썬 증권 데이터 분석 파이썬 입문, 웹 스크레이핑, 트레이딩 전략, 자동 매매](https://book.naver.com/bookdb/book_detail.nhn?bid=16381920)

------



## Explain Directory

------

#### Efficient Portfolio Optimization

코스피 종목 N개 들로 구성된 포트폴리오 최적화를 위한 Tool이다.

Harry Max Markowitz 포트폴리오 이론에 근거해서 펀드 포트폴리오를 구성하게 된다.

DCF Result를 바탕으로 각 종목의 Correlation, Covariance를 Matrix 형태로 계산해서 

위험(표준편차) 대비 목표 수익성이 높은 포트폴리오를 구성하는 것에 목적이 있다.

투자성과 확인지표로써 Sharpe Ratio를 이용해서 가장 효율적인(Sharpe Ratio가 최대가 되는) 포트폴리오를 구성하고, 회귀분석으로 KODEX200 대비 베타값을 도출한다.

아래와 같은 라이브러리들이 사용됨

> pandas | pandas_datareader 
>
> matplotlib | numpy | yfinance
>
> pykiwoom
>
> statsmodels | seaborn



#### Kiwoom API

키움증권에서 제공하는 API를 사용하기 위한 툴들로 PyQt를 쓸 때와 안쓸 때를 구분한다.



#### Finance Data Operation Tool

numpy, matplotlib, pandas 등 데이터 조작에 필요한 툴들의 기본 문법 연습과 결과 들을 포함한다.



#### Get Data Other Theme

주가 데이터(국내, 해외)들을 테마별로 정리하고 받아오는 Tool을 만들었다.

------

