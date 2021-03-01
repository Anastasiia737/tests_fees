# tests_fees

# UNI Fee Formula

**fees_earned**=(reserveUSD2*(liquidityTokenTotalSupply1/liquidityTokenTotalSupply2-1)+reserveUSD2*(1-(math.sqrt(reserve1_1*reserve2_1)/math.sqrt(reserve1_2*reserve2_2))) )*(liquidityTokenBalance1/liquidityTokenTotalSupply1)
fees_earned

+ Must be converted into absolute value!



# BALANCER Fee Formula

**fees_earned_balancer**=(totalSwapFee1-totalSwapFee0)*bpt_balance1/totalShares1
