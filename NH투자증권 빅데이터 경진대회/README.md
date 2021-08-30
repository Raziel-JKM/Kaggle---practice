## [NH투자증권 빅데이터 경진대회](https://dacon.io/competitions/official/235798/data)

### Data

### cus_info.csv(10,000건): 고객 및 주거래계좌 정보

- act_id: 계좌 ID
- sex_dit_cd: 성별
- cus_age_stn_cd: 연령대
- ivs_icn_cd: 투자성향
- cus_aet_stn_cd: 자산구간
- mrz_pdt_tp_sgm_cd: 주거래상품군
- lsg_sgm_cd: Life Style
- tco_cus_grd_cd: 서비스 등급
- tot_ivs_te_sgm_cd: 총 투자기간
- mrz_btp_dit_cd: 주거래업종구분

### stk_bnc_hist.csv(2,573,839건): 국내주식 잔고이력

- act_id: 계좌 ID
- bse_dt: 기준일자
- iem_cd: 종목코드
- bnc_qty: 잔고수량
- tot_aet_amt: 잔고금액
- stk_par_pr: 주당 액면가


### iem_info.csv(3,078건): 종목 정보

- iem_cd: 종목코드
- iem_krl_nm: 종목한글명
- btp_cfc_cd: 종목업종
- mkt_pr_tal_scl_tp_cd: 시가총액 규모유형
- stk_dit_cd: 시장구분


### stk_hld_train.csv(681,472건): 16년 1월 ~ 20년 12월 사이 고객의 국내주식 거래가 종료 된 건

- act_id: 계좌 ID
- iem_cd: 종목코드
- byn_dt: 매수일자
- hold_d: 보유기간(일)


### stk_hld_test.csv(70,596건): 20년 12월 이전에 매수하고 21년 이후에 고객이 전량 매도한 국내주식 보유기간 예측

- act_id: 계좌 ID
- iem_cd: 종목코드
- byn_dt: 매수 일자
- hist_d: 과거 보유일
- submit_id: 제출ID
- hold_d: 보유기간(일)

### sample_submission.csv(70,596건)

- submit_id: 제출 ID
- hold_d: 예측해야 하는 보유기간(일)
