<template>
  <div>
    <div
      class="mobile"
      style="display: flex; flex-direction: column; align-items: flex-end"
    >
      <span style="margin: 0 20px">SMART CONTRACT AUDIT</span>
      <div class="hr"></div>
    </div>
    <div class="desktop" style="height: 30px"></div>
    <div
      class="desktop"
      style="position: absolute; width: 100%; transform: translateY(20px)"
    >
      <div class="container">
        <h4 style="width: 110px !important; direction: rtl">
          SMART CONTRACT AUDIT
        </h4>
      </div>
      <div class="hr desktop" style="z-index: 0"></div>
    </div>
    <div class="container" style="padding-top: 20px; margin: 0 auto 50px">
      <div style="position: relative">
        <div style="display: flex; align-items: flex-end">
          <h1 class="mobile" style="padding: 0 20px">
            WE PROVIDE THE FOLLOWING SERVICES
          </h1>
          <div class="desktop" style="margin-left: 110px">
            <h1
              style="
                padding: 0 0 0 20px;
                position: relative;
                width: fit-content;
                background-color: #d9dbda;
                z-index: 1;
              "
            >
              WE PROVIDE THE
            </h1>
            <h1
              style="
                padding: 0 50px 0 20px;
                position: relative;
                width: fit-content;
                background-color: #d9dbda;
                z-index: 1;
              "
            >
              FOLLOWING SERVICES
            </h1>
          </div>
        </div>
      </div>
      <ul
        class="alpina desktop"
        style="
          list-style-type: none;
          font-size: 20px;
          margin: 10px 0 10px 130px;
          max-width: 540px;
        "
      >
        <li>
          Check against the latest attack vectors and give you a full pdf audit
          report.
        </li>
        <li>Check against any logical errors.</li>
        <li>
          We leverage a combination of static analysis, automated tools, and a
          robust manual review process to provide industry-leading security
          recommendations to project teams.
        </li>
        <li>
          We assist project team's in resolve any outstanding issues or
          implementing our recommendations.
        </li>

        <li>
          To get started, give us the link to the deployed smart contract on the
          testnet/mainnet
        </li>
        <li>or link to github repo</li>
        <li>or the contracts zipped</li>
        <li>
          additionally if you have tests written it will greatly improve the
          audit delivery time
        </li>
      </ul>
      <ul
        class="alpina mobile"
        style="list-style-type: none; font-size: 20px; margin: 20px"
      >
        <li>
          Check against the latest attack vectors and give you a full pdf audit
          report.
        </li>
        <li>Check against any logical errors.</li>
        <li>
          We leverage a combination of static analysis, automated tools, and a
          robust manual review process to provide industry-leading security
          recommendations to project teams.
        </li>
        <li>
          We assist project team's in resolve any outstanding issues or
          implementing our recommendations.
        </li>

        <li>
          To get started, give us the link to the deployed smart contract on the
          testnet/mainnet
        </li>
        <li>or link to github repo</li>
        <li>or the contracts zipped</li>
        <li>
          additionally if you have tests written it will greatly improve the
          audit delivery time
        </li>
      </ul>

      <div style="height: 10px"></div>

      <div
        class="margin"
        style="
          margin: 10px 5px 10px 5px auto;
          padding: 10px 30px;
          text-align: center;
          max-width: 540px;
          border-left: 1px solid #0f2a63;
          border-right: 1px solid #0f2a63;
          border-radius: 50px;
        "
      >
        IF NO VULNERABILITIES OR ISSUES WERE FOUND AND YOUR CONTRACT IS 100%
        CORRECT THEN THE AUDIT IS FREE
      </div>
      <div
        class="desktop"
        style="
          margin: auto;
          display: flex;
          max-width: 540px;
          align-items: flex-start;
        "
      >
        <div
          style="
            background-color: #fff;
            margin-right: 10px;
            border: 1px solid #0f2a63;
            border-radius: 50%;
            width: 30%;
            padding: 20px 0;
            display: flex;
            justify-content: center;
            align-items: center;
          "
        >
          NOTE THAT
        </div>
        <ul style="width: 70%; margin-top: 20px">
          <li>100% Refund if we don't meet the deadline</li>
          <li>
            The audit is confidental. It's up to you to do whatever you want
            with it after
          </li>
          <li>
            We can only audit smart contracts that are on etherum, binance smart
            chain (bsc), polygon (matic), fantom, avalance's c-chain, harmony
            one, kucoin (kcc), huobi eco, arbitrum, or any other evm-compatible
            side-chain or 12 chain
          </li>
        </ul>
      </div>

      <div class="mobile" style="margin: 20px">
        <div
          style="
            width: 150px;
            background-color: #fff;
            border: 1px solid #0f2a63;
            border-radius: 50%;
            padding: 20px 0;
            display: flex;
            justify-content: center;
            align-items: center;
          "
        >
          NOTE THAT
        </div>
        <ul style="margin-top: 20px">
          <li>100% Refund if we don't meet the deadline</li>
          <li>
            The audit is confidental. It's up to you to do whatever you want
            with it after
          </li>
          <li>
            We can only audit smart contracts that are on etherum, binance smart
            chain (bsc), polygon (matic), fantom, avalance's c-chain, harmony
            one, kucoin (kcc), huobi eco, arbitrum, or any other evm-compatible
            side-chain or 12 chain
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SmartContractAudit",
};
</script>
