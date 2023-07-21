<template>
  <div class="w-full dark:bg-[#1E3140]">
    <!-- Hero section -->
    <section id="hero" class="w-full pb-24 dark:bg-[#1E3140]">
      <BaseSection>
        <div class="col-span-12 lg:col-span-8 mt-12 xl:mt-10 sm:space-y-6 px-6 text-center sm:text-left py-28">
          <span data-aos="fade-right" data-aos-once="true" class="text-base text-gradient font-semibold uppercase">20
            - 21
            September 2023, Festival Arena - Dubai Festival City</span>
          <h1 data-aos="fade-right" data-aos-once="true"
            class="text-[4rem] sm:text-5xl xl:text-5xl font-bold leading-tight capitalize sm:pr-8 xl:pr-10 py-3">
            <span class="text-header-gradient py-3 ">Crypto Rabbit Dubai 2023</span>
          </h1>
          <p data-aos="fade-down" data-aos-delay="300" class="paragraph hidden sm:block dark:text-white">
            Dubai’s Largest Cryptocurrency Summit
          </p>
          <div data-aos="fade-up" data-aos-delay="700"
            class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4 mt-2">
            <BaseButton
              class="max-w-full px-8 py-4 bg-gradient-to-r from-[#468ef9] to-[#0c66ee] border border-[#0c66ee] text-white">
              Buy Ticket
            </BaseButton>
          </div>
        </div>
        <div class="hidden sm:block col-span-12 lg:col-span-4 py-12">
          <div class="w-full">
            <img data-aos="fade-up" data-aos-once="true" :src="require('~/assets/img/hero-image.webp')" class="-mt-4"
              alt="" />
          </div>
        </div>
        <img data-aos="fade-up" data-aos-delay="300" :src="require('~/assets/img/pattern/ellipse-1.png')"
          class="hidden sm:block absolute bottom-12 xl:bottom-16 left-4 xl:left-0 w-6" />
        <img data-aos="fade-up" data-aos-delay="300" :src="require('~/assets/img/pattern/ellipse-2.png')"
          class="hidden sm:block absolute top-4 sm:top-10 right-64 sm:right-96 xl:right-[32rem] w-6" />
        <img data-aos="fade-up" data-aos-delay="300" :src="require('~/assets/img/pattern/ellipse-3.png')"
          class="hidden sm:block absolute bottom-56 right-24 w-6" />
        <img data-aos="fade-up" data-aos-delay="300" :src="require('~/assets/img/pattern/star.png')"
          class="hidden sm:block absolute top-20 sm:top-28 right-16 lg:right-0 lg:left-[30rem] w-8" />
      </BaseSection>
    </section>

    <!-- Crypto statistic section -->
    <section
      class="max-w-screen-xl mx-2 sm:mx-auto px-4 sm:px-6 lg:px-0 py-5 pb-20 sm:py-8 rounded-[2.25rem] sm:rounded-xl dark:bg-[#1E3140] bg-white shadow-lg sm:shadow-md transform lg:-translate-y-15">
      <h1 data-aos="fade-down"
        class="text-[4rem] sm:text-5xl xl:text-5xl font-bold leading-tight capitalize sm:pr-8 xl:pr-10 py-3 text-center">
        <span class="text-header-gradient py-3 ">About Event</span>
      </h1>
      <p data-aos="fade-up" data-aos-delay="300" class="paragraph hidden sm:block text-center px-36 dark:text-white">
        CryptoRABBIT is the blockchain conference network bringing together the key players of crypto industry and experts
        to redefine the future of finance. The edition of the CryptoRABBIT will take place during on August 30, 2023 in
        Dubai, with the world’s top crypto companies and blockchain entrepreneurs. Today, UAE, specifically Dubai is
        gearing up to become a global crypto hub. Thus, CryptoRABBIT will be the gathering in the region on behalf of the
        world of blockchain and cryptocurrency, with a wide range of topics focused on the financial technologies of the
        future, extensive networking opportunities and participation from more than 40 countries.
      </p>
      <div class="flex justify-around my-10 flex-wrap">

        <div data-aos="fade-right" data-aos-delay="300"
          class="max-w-sm bg-white border0 rounded-lg shadow dark:bg-gray-800 my-4"
          style="background: linear-gradient(169.4deg, #3984f4 -6.01%, #0cd3ff 36.87%, #2f7cf0 78.04%, #0e65e8 103.77%);">

          <img class="rounded-t-lg w-full " :src="require('~/assets/img/designs/designs-01-370x170-1.png')" alt="" />

          <div class="p-5">
            <h5 class="mb-2 text-2xl font-normal tracking-tight text-gray-900 dark:text-white">Expo</h5>
            <p class="mb-3 font-normal text-white text-[0.8rem]">Putting in forefront of thousands of
              traders and investors, top cryptocurrency brands disclose their finest digital currency products and
              services.</p>
          </div>
        </div>
        <div data-aos="fade-up" data-aos-delay="300"
          class="max-w-sm bg-white border0 rounded-lg shadow dark:bg-gray-800 my-4"
          style="background: linear-gradient(169.4deg, #3984f4 -6.01%, #0cd3ff 36.87%, #2f7cf0 78.04%, #0e65e8 103.77%);">

          <img class="rounded-t-lg w-full" :src="require('~/assets/img/designs/designs-02-370x170-1.png')" alt="" />

          <div class="p-5">
            <h5 class="mb-2 text-2xl font-normal tracking-tight text-gray-900 dark:text-white">Conference</h5>
            <p class="mb-3 font-normal text-white text-[0.8rem]">Top industry experts provide traders, investors, and
              businesses with meaningful insights and the most recent updates about cryptocurrencies.</p>
          </div>

        </div>
        <div data-aos="fade-left" data-aos-delay="300"
          class="max-w-sm bg-white border0 rounded-lg shadow dark:bg-gray-800 my-4"
          style="background: linear-gradient(169.4deg, #3984f4 -6.01%, #0cd3ff 36.87%, #2f7cf0 78.04%, #0e65e8 103.77%);">

          <img class="rounded-t-lg w-full" :src="require('~/assets/img/designs/designs-03-370x170-1.png')" alt="" />

          <div class="p-5">
            <h5 class="mb-2 text-2xl font-normal tracking-tight text-gray-900 dark:text-white">Awards</h5>
            <p class="mb-3 font-normal text-white text-[0.8rem]">
              A quick glance at the best cryptocurrency receiving awards at the Ceremony..</p>
          </div>

        </div>
      </div>
    </section>
    <section class=" dark:bg-[#1E3140] py-10">
      <h1 data-aos="fade-down"
        class="text-[4rem] sm:text-5xl xl:text-5xl font-bold leading-tight capitalize sm:pr-8 xl:pr-10 text-center">
        <span class="text-header-gradient py-3 ">DATE</span>
      </h1>
      <p data-aos="fade-up" data-aos-delay="300"
        class="paragraph hidden sm:block text-center px-36 py-10 text-[2rem] dark:text-white">
        August 30, 2023 at 5:30 PM. Place - Dubai, ATLANTIS, THE PALM.
      </p>
    </section>

    <section class=" relative max-w-full sm:mx-4 my-5 py-3  rounded-2xl overflow-hidden">
      <div class="relative max-w-screen-xl px-4 sm:px-2 mx-auto grid grid-cols-12 gap-x-6">
        <LandingTradingToolImage class="sm:hidden" />
        <div data-aos="fade-right" class="col-span-12 lg:col-span-8 space-y-8 sm:space-y-6 px-4 sm:px-6 mt-8">
          <h2 class="text-4xl font-semibold" data-aos="fade-down"><span class="text-header-gradient">Discussion Topics:
            </span></h2>
          <div class="space-y-2 dark:text-white">
            <h4 class="text-lg font-medium" data-aos="fade-right">Identifying the gamechanging trends in the web 3.0
              ecosystem </h4>
            <p class="paragraph text-sm xl:text-base mx-3 dark:text-white" data-aos="fade-right">
              1)WHAT WEB 3.0 MEANS FOR ENTERPRISES (Sunny Lu)
            </p>
            <p class="paragraph text-sm xl:text-base mx-3 dark:text-white" data-aos="fade-left">
              2)VALUE CREATION IN THE METAVERSE (Gracy Chen)
            </p>
            <p class="paragraph text-sm xl:text-base mx-3 dark:text-white" data-aos="fade-right">
              3)THE ROLE OF STABLECOINS IN A DECENTRALIZED ECOSYSTEM (Nena Dokuzov & Jean Charles Gaudechon)
            </p>
            <p class="paragraph text-sm xl:text-base mx-3 dark:text-white" data-aos="fade-left">
              4)DAOS: NEW BREED OF INTERNET-NATIVE ORGANIZATIONS (Max Kordek)
            </p>
            <p class="paragraph text-sm xl:text-base mx-3 dark:text-white" data-aos="fade-right">
              5)MAXIMIZING ESG IMPACT WITH BLOCKCHAIN (Helen Hai)
            </p>
            <p class="paragraph text-sm xl:text-base mx-3 dark:text-white" data-aos="fade-left">
              6)BRIDGING DEFI AND CEFI (Jason Allegrante)
            </p>
            <p class="paragraph text-sm xl:text-base mx-3 dark:text-white" data-aos="fade-right">
              7)WEB 3 GAMING: THE NEW FRONTIER? (Sunny Lu)
            </p>
            <p class="paragraph text-sm xl:text-base mx-3 dark:text-white" data-aos="fade-left">
              8)DECRYPTING THE REGULATORY LANDSCAPE OF VIRTUAL ASSETS (Reece Merrick)
            </p>
            <p class="paragraph text-sm xl:text-base mx-3 dark:text-white" data-aos="fade-right">
              9)CENTRAL BANK DIGITAL CURRENCIES, AND CROSS-BORDER PAYMENTS (Mohammed Alblooshi)
            </p>
            <p class="paragraph text-sm xl:text-base mx-3 dark:text-white" data-aos="fade-left">
              10)WEB 3: THE FUTURE IS HERE AND NOW (Sunny Lu)
            </p>
            <p class="paragraph text-sm xl:text-base mx-3 dark:text-white" data-aos="fade-right">
              11)NFT MARKET OVERVIEW: TRENDS & OPPORTUNITIES (Alex Zinder & Nicole Purin)
            </p>
            <p class="paragraph text-sm xl:text-base mx-3 dark:text-white" data-aos="fade-up">
              12)INTEROPERABILITY - CHALLENGES AND OPPORTUNITIES (Dina Sam'an)
            </p>
          </div>
        </div>
        <LandingTradingToolImage data-aos="fade-left" class="hidden sm:block" />
      </div>
    </section>

    <section class="dark:bg-[#1E3140] relative max-w-full sm:mx-4 xl:mx-10 shadow sm:rounded-2xl overflow-hidden">
      <h1 data-aos="fade-down"
        class="text-[4rem] sm:text-5xl xl:text-5xl font-bold leading-tight capitalize sm:pr-8 xl:pr-10 py-3 text-center">
        <span class="text-header-gradient py-3 ">Speakers</span>
      </h1>
      <div class="flex justify-around flex-wrap">
        <LandingCard name="Alex Zinder" description='(Ledger Enterprise)' url="3)Alex-Zinder.png"
          animateCard="fade-right">
        </LandingCard>
        <LandingCard name="Dina Sam'an" description='(CoinMENA)' url="9)Diana.png" animateCard="fade-down"></LandingCard>
        <LandingCard name="Gracy Chen" description='(Bitget)' url="4)Gracy-Chen.png"></LandingCard>
        <LandingCard name="Helen Hai" description='(Binance)' url="2)Helen-Hai.png" animateCard="fade-left"></LandingCard>
        <LandingCard name="Jason Allegrante" description='(Fireblocks)' url="12)Jason-Allegrante.png"
          animateCard="fade-right">
        </LandingCard>
        <LandingCard name="Jean Charles-Gaudechon" description='(OneFootball Labs)' url="10)Jean-Charles-Gaudechon.png">
        </LandingCard>
        <LandingCard name="Max Kordek" description='(Lisk)' url="4)Gracy-Chen.png" animateCard="fade-down"></LandingCard>
        <LandingCard name="Nicole Purin" description='(OKX)' url="11)Nicole-Purin.png" animateCard="fade-left">
        </LandingCard>
        <LandingCard name="Mohammed Alblooshi" description='(Dubai International Financial Centre Authority)'
          url="5)Mohammed-Alblooshi.png" animateCard="fade-right">
        </LandingCard>
        <LandingCard name="Nena Dokuzov" description='(Alserkal Group)' url="7)Nena-Dokuzov.png" animateCard="fade-down">
        </LandingCard>
        <LandingCard name="Reece Merrick" description='(Ripple)' url="8)Reece-Merrick.png"></LandingCard>
        <LandingCard name="Sunny Lu" description='(Vechain)' url="1)Sunny-Lu.png" animateCard="fade-left"></LandingCard>
      </div>
    </section>

    <!-- FAQ section -->
    <section
      class="max-w-screen-lg mx-2 sm:mx-auto px-4 sm:px-6 lg:px-0 sm:py-8 rounded-[2.25rem] sm:rounded-xl shadow-lg sm:shadow-md flex justify-center items-center flex-wrap">
      <h1 data-aos="fade-down"
        class="text-[4rem] sm:text-5xl xl:text-5xl font-bold leading-tight capitalize sm:pr-8 xl:pr-10 py-5 text-center">
        <span class="text-header-gradient py-3 ">Sponsors</span>
      </h1>
      <div class="flex justify-center items-center flex-wrap">
        <LandingFlipCard url="1)Woodstock Fund.png" animateFlip="fade-right"></LandingFlipCard>
        <LandingFlipCard url="7)Tykhe Block Ventures.png" animateFlip="fade-down"></LandingFlipCard>
        <LandingFlipCard url="4)Momentum6.png" animateFlip="fade-up"></LandingFlipCard>
        <LandingFlipCard url="8)18 Ventures.png" animateFlip="fade-left"></LandingFlipCard>
        <LandingFlipCard url="5)888vc.png" animateFlip="fade-right"></LandingFlipCard>
        <LandingFlipCard url="3)Annex-Investments.png" animateFlip="fade-up"></LandingFlipCard>
        <LandingFlipCard url="2)C3.png" animateFlip="fade-down"></LandingFlipCard>
        <LandingFlipCard url="6)DSA-Investments.png" animateFlip="fade-left"></LandingFlipCard>
      </div>
    </section>
    <section class=" z-10 w-full text-neutral-800 bg-sky-100 dark:bg-[#1E3140] w-full fixed bottom-0 py-5 px-5">
      <div class="flex gap-5 dark:text-white">
        <div>
          <span class="countdown font-mono text-4xl">
            <span :style="`--value: ${days}`"></span>
          </span>
          days
        </div>
        <div>
          <span class="countdown font-mono text-4xl">
            <span :style="`--value: ${hours}`"></span>
          </span>
          hours
        </div>
        <div>
          <span class="countdown font-mono text-4xl">
            <span :style="`--value: ${minutes}`"></span>
          </span>
          min
        </div>
        <div>
          <span class="countdown font-mono text-4xl">
            <span :style="`--value: ${seconds}`"></span>
          </span>
          sec
        </div>
      </div>
    </section>

    <div class="w-full my-15 flex justify-center">
      <a v-smooth-scroll data-aos="flip-down" data-aos-delay="150" href="#navbar"
        class="px-6 py-3 flex items-center space-x-2 bg-[#FAFAFA] hover:bg-gray-100 hover:shadow-md border border-[#DDDDDD] rounded-md text-gray-700">
        <span>Back to top</span>
        <ArrowUpIcon :size="20" />
      </a>
    </div>
  </div>
</template>

<script>
import aosMixin from '@/mixins/aos'
export default {
  name: 'IndexPage',
  mixins: [aosMixin],
  data() {
    return {
      days: 0,
      hours: 0,
      minutes: 0,
      seconds: 0,
      targetDate: new Date('2023-08-30T17:30:00').getTime(), // Adjust the target date as per your requirements
      selected: 0,
      dropdownConcurency: false,
      dropdownCrypto: false,
      currencySelected: {
        img: 'country-icon/eng.png',
        name: 'USD',
      },
      currencies: [
        {
          img: 'country-icon/eng.png',
          name: 'USD',
        },
      ],
      cryptoSelected: {
        img: 'crypto-icon/bitcoin.png',
        name: 'BTC',
      },
      cryptocurrencies: [
        {
          img: 'crypto-icon/bitcoin.png',
          name: 'BTC',
        },
      ],
      trendings: [
        {
          id: 1,
          name: 'Bitcoin',
          price: 43180.13,
          logo: 'bitcoin.png',
          increase: true,
          data: [40, 35, 60, 75, 60, 75, 50],
        },
        {
          id: 2,
          name: 'Ethereum',
          price: 3480.65,
          logo: 'ethereum.png',
          increase: false,
          data: [25, 30, 60, 50, 80, 55, 80],
        },
        {
          id: 3,
          name: 'Solana',
          price: 150.2,
          logo: 'solana.png',
          increase: true,
          data: [40, 45, 40, 80, 50, 60, 35],
        },
        {
          id: 4,
          name: 'Dogecoin',
          price: 0.1572,
          logo: 'dogecoin.png',
          increase: true,
          data: [35, 70, 60, 80, 50, 60, 40],
        },
      ],
      topGainers: [
        {
          id: 1,
          name: 'PAPPAY',
          price: 0.00374,
          logo: 'pappay.png',
          increase: true,
          data: [30, 50, 45, 60, 70, 40, 45],
        },
        {
          id: 2,
          name: 'Bitcoin Asia',
          price: 0.02096,
          logo: 'bitcoin-asia.png',
          increase: true,
          data: [25, 60, 50, 60, 35, 50, 70],
        },
        {
          id: 3,
          name: 'MoonRock',
          price: 0.004907,
          logo: 'moonrock.png',
          increase: true,
          data: [40, 35, 40, 25, 50, 70, 45],
        },
        {
          id: 4,
          name: 'NinjaFloki',
          price: 0.000123,
          logo: 'ninjafloki.png',
          increase: true,
          data: [45, 35, 40, 30, 25, 45, 35],
        },
      ],
      recents: [
        {
          id: 1,
          name: 'MetaCraft',
          price: 0.0608,
          logo: 'metacraft.png',
          increase: false,
          data: [40, 50, 45, 60, 35, 40, 45],
        },
        {
          id: 2,
          name: 'Frog',
          price: 0.5875,
          logo: 'frog.png',
          increase: false,
          data: [25, 50, 45, 48, 40, 60, 45],
        },
        {
          id: 3,
          name: 'Musk Doge',
          price: 0.04041,
          logo: 'musk-doge.png',
          increase: true,
          data: [25, 35, 60, 45, 50, 45, 45],
        },
        {
          id: 4,
          name: '2SHARE',
          price: 1366.24,
          logo: '2share.png',
          increase: true,
          data: [35, 30, 60, 50, 35, 45, 40],
        },
      ],
      accordions: [
        {
          title: 'Why should I choose NEFA?',
          description:
            "We're industry pioneers, having been in the cryptocurrency industry since 2016. We've facilitated more than 21 billion USD worth of transactions on our exchange for customers in over 40 countries. Today, we're trusted by over 8 million customers around the world and have received praise for our easy-to-use app, secure wallet, and range of features.",
        },
        {
          title: 'How secure is NEFA?',
          description:
            "We're industry pioneers, having been in the cryptocurrency industry since 2016. We've facilitated more than 21 billion USD worth of transactions on our exchange for customers in over 40 countries. Today, we're trusted by over million customers around the world and have received praise for our easy-to-use app, secure wallet, and range of features.",
        },
        {
          title: 'Do I have to buy a whole Bitcoin?',
          description:
            "We're industry pioneers, having been in the cryptocurrency industry since 2016. We've facilitated more than 21 billion USD worth of transactions on our exchange for customers in over 40 countries. Today, we're trusted by over million customers around the world and have received praise for our easy-to-use app, secure wallet, and range of features.",
        },
        {
          title: 'How do I actually buy Bitcoin?',
          description:
            "We're industry pioneers, having been in the cryptocurrency industry since 2016. We've facilitated more than 21 billion USD worth of transactions on our exchange for customers in over 40 countries. Today, we're trusted by over million customers around the world and have received praise for our easy-to-use app, secure wallet, and range of features.",
        },
      ],
      steps: [
        {
          img: 'sign-up.png',
          title: 'Sign Up',
          description:
            'Sign up for your free NEFA Wallet on web, iOS or Android and follow our easy process to set up your profile',
        },
        {
          img: 'fund.png',
          title: 'Fund',
          description:
            'Choose your preferred payment method such as bank transfer or credit card to top up your NEFA Wallet',
        },
        {
          img: 'buy-crypto.png',
          title: 'Buy Crypto',
          description:
            'Buy Bitcoin or Ethereum, then securely store it in your Wallet or send it on easily to your friends anywhere',
        },
      ],
    }
  }, mounted() {
    this.updateCountdown();
    setInterval(this.updateCountdown, 1000);
    setTimeout(() => {
      window.scrollBy(0, 1);
    }, 500);
  },
  methods: {
    updateCountdown() {
      const now = new Date().getTime();
      const remainingTime = this.targetDate - now;

      this.days = Math.floor(remainingTime / (1000 * 60 * 60 * 24));
      this.hours = Math.floor((remainingTime % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      this.minutes = Math.floor((remainingTime % (1000 * 60 * 60)) / (1000 * 60));
      this.seconds = Math.floor((remainingTime % (1000 * 60)) / 1000);
    },
  },
}
</script>
<style scoped>
.text-header-gradient {
  background: rgb(57, 132, 244);
  background: linear-gradient(169.4deg, #3984f4 -6.01%, #0cd3ff 36.87%, #2f7cf0 78.04%, #0e65e8 103.77%);
  background-clip: text;
  -webkit-text-fill-color: transparent;
}

.bg-partner {
  background: url('../assets/img/partner/background.png');
  background-size: cover;
  background-position: center;
}

.bg-trading-tools {
  background: url('../assets/img/bg-trading-tools.webp');
  background-size: cover;
  background-position: center;
}

.max-h-0 {
  max-height: 0;
}

.flip-card {
  perspective: 1000px;
  width: 200px;
  height: 200px;
}

.flip-card-inner {
  width: 100%;
  height: 100%;
  transition: transform 0.6s;
  transform-style: preserve-3d;
}

.flip-card.flipped .flip-card-inner,
.flip-card.flipped.is-hovered .flip-card-inner {
  transform: rotateY(180deg);
}

.flip-card-front,
.flip-card-back {
  position: absolute;
  width: 100%;
  height: 100%;
  backface-visibility: hidden;
}

.flip-card-front {
  background-color: #f1f1f1;
  transition: background-color 0.3s;
}

.flip-card-back {
  background-color: #000000;
  color: rgb(0, 0, 0);
  transform: rotateY(180deg);
  transition: background-color 0.3s;
}


.flip-card:hover .flip-card-front {
  background-color: #ccc;
}

.flip-card:hover .flip-card-back {
  background-color: #555;
}
</style>
