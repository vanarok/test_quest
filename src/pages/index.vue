<script setup lang="ts">
</script>

<template>
  <div relative text-white>
    <div h-200 w-full bg-black style="background-image: url('/background.jpeg'); background-size: cover; background-position: center; background-repeat: no-repeat; background-attachment: fixed;">
      <div text-sm absolute top-0 left-0 h-20 w-full px-30 pt-10>
        <div flex items-center justify-between>
          <span drop-shadow-2xl>ATLANT MEIDA</span>

          <span flex gap-4>
            <span drop-shadow-2xl>WORK</span>
            <span drop-shadow-2xl>ABOUT</span>
            <span drop-shadow-2xl>CONTACT</span>
          </span>
        </div>
      </div>

      <div pt-50 max-w-xl mx-30>
        <div drop-shadow-2xl text-7xl line-height-5rem>
          How to get new 50-200 clients every month?
        </div>
        <div drop-shadow-2xl text-sm text-neutral-1 max-w-16rem mt-6>
          We have attracted over 500,000 new clients via Facebook & Instagram
          ads for fitness studios in the last 2 years
        </div>
        <button bg-orange-1 p-4 text-sm text-black w-70 mt-10>
          YES! I WANT THIS!
        </button>
      </div>
    </div>

    <div text-black pt-50 mx-30>
      <div text-6xl>
        We offer a <br />
        complete solution
      </div>

      <div flex mt-20>
        <div flex flex-col w-180 text-lg gap-3>
          <i class="i-carbon:flash" text-2xl />
          Quiz with high conversion
          <div text-sm text-neutral>
            We create a quiz with <br />
            a conversion of 30%
          </div>
        </div>
        <div flex flex-col w-180 text-lg gap-3>
          <i class="i-carbon:copy" text-2xl />
          Selling copywriting
          <div text-sm text-neutral>
            We think over the meanings <br />
            and offers motivation to buy your <br />
            product event without a promotion
          </div>
        </div>
        <div flex flex-col w-180 text-lg gap-3>
          <i class="i-carbon:edit" text-2xl />
          Automation
          <div text-sm text-neutral>
            New requests come to your sales <br />
            depatrament within 3-5 minutes.<br />
            Stay ahead of your competitors
          </div>
        </div>
        <div flex flex-col w-180 text-lg gap-3>
          <i class="i-carbon:mobile" text-2xl />
          Modern creatives
          <div text-sm text-neutral>
            We create stylish creatives that provoke <br />
            people to attend your workouts.<br />
            Unlimited professional creatives
          </div>
        </div>
      </div>

      <div mt-20>
        <div text-6xl>
          Hundreds of successful projects from different markets and countries
        </div>

        <div mt-10 text-sm text-neutral-9>
          Years of Proven Advertising Strategies<br />
          we build a lead generation system that <br />
          pays off in the first month
          <div mt-20 flex gap-3>
            <img
              v-for="i in 3"
              :key="i"
              :src="`/photo${i}.jpeg`"
              h-180
              w-80
              bg-black
              object-cover
            />
          </div>
        </div>
        <button p-4 text-sm bg-orange-9 text-white w-70 mt-20 mx-auto block>
          VIEW ALL CASES
        </button>
      </div>
    </div>

    <div text-black pt-50 mx-30>
      <div text-6xl>
        How we are working <br />
        and get results
      </div>

      <div mt-20>
        <div flex flex-row justify-between pr-60>
          <div text-2xl>
            Free consultation and strategy
          </div>
          <div text-neutral flex flex-col gap-2 max-w-xs>
            <div>Audit your advertising campaigns and find growth points</div>
            <div>
              Analyze your website, social media porfiles and give
              recommendations for improvement
            </div>
            <div>
              Prepare for you a preliminary staegoy and work plan for your
              project
            </div>
            <div>Sign an agreement</div>
          </div>
        </div>

        <div border-t-neutral border-t my-15 />

        <div flex flex-row justify-between pr-60>
          <div text-2xl>
            Research and preparation <br />
            of promotional material
          </div>
          <div text-neutral flex flex-col gap-2 max-w-xs>
            <div>Create a working chat and get to know the team</div>
            <div>Briefing and study the product</div>
            <div>Analyze competitors and target audience</div>
            <div>Prepare advertising creatives and text</div>
            <div>Coordinate everything with you</div>
          </div>
        </div>
      </div>

      <div border-t-neutral border-t my-15 />

      <div flex flex-row justify-between pr-60>
        <div text-2xl>
          Setting up an account and services
        </div>
        <div text-neutral flex flex-col gap-2 max-w-xs>
          <div>Installing Facebook Pixel for Retargeting Campaigns</div>
          <div>Installing Google Analytics to control ads</div>
          <div>
            Integrate with the CRM system for prompt<br />
            transfer of requests
          </div>
          <div>Setting up an ad account and getting ready to launch</div>
        </div>
      </div>

      <div border-t-neutral border-t my-15 />

      <div flex flex-row justify-between pr-60>
        <div text-2xl>
          Launch, optimization and reporting
        </div>
        <div text-neutral flex flex-col gap-2 max-w-xs>
          <div>Launch advertising campaigns</div>
          <div>Testing various hypotheses</div>
          <div>Scaling working models</div>
          <div>Optimize indicators</div>
          <div>Provide a control system and daily reporting</div>
        </div>
      </div>
    </div>

    <div mt-30 text-black pt-40 mx-30>
      <div text-6xl>
        We create web banners<br />that bring hundreds of<br />applications and
        purchases
      </div>
      <div mt-10 text-sm text-neutral-9>
        The success of of advertising campaigns largely depends on
        advertising<br />
        creatives, so our studio employs specialists with mnay years of
        experience <br />
        in creating performance creatives from static banners to motion design
      </div>

      <div mt-20 flex gap-3>
        <img v-for="i in 3" :key="i" object-cover :src="`/photo${3 + i}.jpeg`" h-100 w-80 bg-black />
      </div>
    </div>

    <div mt-30 text-black pt-40 mx-30>
      <div text-6xl>
        Major brands trust us <br />with their reputation
      </div>

      <div mt-20 flex gap-3>
        <img v-for="i in 5" :key="i" object-cover :src="`/logo${i}.jpeg`" h-30 w-100 bg-black />
      </div>

      <div mt-30 text-3xl>
        Write your whatsapp number where to send cases
      </div>
      <div mt-10 flex flex-row text-sm gap-10 text-neutral-6>
        <div>
          <div>Whatsapp number</div>
          <input
            type="text"
            placeholder="PHONE"
            mt-6
            px-8
            py-4
            border
            border-solid
            border-black
            w-100
          />
        </div>
        <div>
          <div>Business activities</div>
          <input
            type="text"
            placeholder="FITNESS STUDIO/ONLINE CLASS/E-COMM ETC"
            mt-6
            px-8
            py-4
            border
            border-solid
            border-black
            w-120
          />
        </div>
        <button mt-11 w-60 p-4 h-13.5 text-sm bg-orange-9 text-white>
          SEND
        </button>
      </div>
    </div>

    <div mt-50 text-black h-130 mx-30 w-100w bg-orange-50 p-30>
      <div flex flex-row justify-around>
        <div bg-black rounded-full h-70 w-70 style="background-image: url('/human4.jpeg'); background-size: cover; background-position: top" />
        <div flex flex-col gap-2 justify-center>
          <div>Founder of Atlant Media</div>
          <div text-5xl>
            Mikhail Plotnikov
          </div>
          <div mt-10 text-sm text-neutral-7>
            Our mission is to help companies become market leaders and<br />
            communicate the value and benefits of their product to people
            <br />around the world through social media advertising
          </div>
        </div>
      </div>
    </div>

    <div mt-30 text-black pt-40 mx-30>
      <div text-6xl>
        The result<br />
        of collaboration
      </div>
      <div grid grid-cols-3 gap-row-20 mt-20 w-4xl>
        <div flex flex-col w-180 text-lg gap-3>
          <i class="i-carbon:flash" text-3xl />
          Control only your internal<br />
          business processes - we<br />
          are an independent unit
        </div>
        <div flex flex-col w-180 text-lg gap-3>
          <i class="i-carbon:cafe" text-3xl />
          Get a short and complete<br />
          report on advertising<br />
          daily/weekly/monthly
        </div>
        <div flex flex-col w-180 text-lg gap-3>
          <i class="i-carbon:logo-flickr" text-3xl />
          Advertising without<br />
          stress, deadline<br />
          failures and blocking
        </div>
        <div flex flex-col w-180 text-lg gap-3>
          <i class="i-carbon:ai-launch" text-3xl />
          Stop wasting money<br />
          on non-working tools
        </div>
        <div flex flex-col w-180 text-lg gap-3>
          <i class="i-carbon:application-web" text-3xl />
          Scalable system for <br />
          attracting new customers
        </div>
        <div flex flex-col w-180 text-lg gap-3>
          <i class="i-carbon:align-vertical-bottom" text-3xl />
          Let's make you<br />
          a market leader
        </div>
      </div>
    </div>

    <div mt-30 text-black pt-40 mx-30>
      <div text-6xl>
        What our clients <br />
        say about us
      </div>

      <div mt-20 flex gap-10>
        <div>
          <div style="background-image: url('/human1.jpeg'); background-size: cover; background-position: top;" src="/human1.jpeg" h-110 w-80 bg-black />

          <div flex flex-row mt-6>
            <div flex flex-col>
              <div text-sm text-neutral>
                Fitness coach
              </div>
              <div text-2xl mt-2>
                Anastasiya Lunegova
              </div>
            </div>
          </div>
        </div>

        <div>
          <div style="background-image: url('/human2.jpeg'); background-size: cover; background-position: top;" h-110 w-80 bg-black />

          <div flex flex-row mt-6>
            <div flex flex-col>
              <div text-sm text-neutral>
                Smart Trainer Studio
              </div>
              <div text-2xl mt-2>
                Natalya Chuprina
              </div>
            </div>
          </div>
        </div>

        <div>
          <div style="background-image: url('/human3.jpeg'); background-size: cover; background-position: top;" h-110 w-80 bg-black />

          <div flex flex-row mt-6>
            <div flex flex-col>
              <div text-sm text-neutral>
                Vogue Fitness
              </div>
              <div text-2xl mt-2>
                Vitaly Kharitoshin
              </div>
            </div>
          </div>
        </div>
      </div>

      <div mt-40 text-3xl>
        Book a free audit and advertising stategy for your project
      </div>
      <div mt-10 flex flex-row text-sm gap-10 text-neutral-6>
        <div>
          <div>Whatsapp number</div>
          <input
            type="text"
            placeholder="PHONE"
            mt-6
            px-8
            py-4
            border
            border-solid
            border-black
            w-100
          />
        </div>
        <div>
          <div>Business activities</div>
          <input
            type="text"
            placeholder="FITNESS STUDIO/ONLINE CLASS/E-COMM ETC"
            mt-6
            px-8
            py-4
            border
            border-solid
            border-black
            w-120
          />
        </div>
        <button mt-11 w-60 p-4 h-13.5 text-sm bg-orange-9 text-white>
          SEND
        </button>
      </div>
    </div>

    <div
      h-70
      w-full
      bg-neutral-8
      mt-50
      flex
      items-center
      justify-center
      text-sm
    >
      <div w-100 ml-30>
        Contact
        <div text-xs text-neutral mt-4>
          +7 (999) 860 18-42 <br />
          dvizh.marketing@gmail.com
        </div>
        <div text-xs text-neutral-5 mt-20>
          ATLANT MEDIA L.L.C-FZ
        </div>
      </div>
      <div w-150>
        Address
        <div mt-4 text-xs text-neutral>
          Business Center 1, M Floor, The Meydan, <br />
          Hotel, Nad AI Sheba, Dbui, U.A.E.
        </div>
        <div mt-4 text-xs text-neutral>
          General Manager<br />Mikhail Plotnikov
        </div>
        <div mt-8 text-xs text-neutral-5>
          Privacy Policy
        </div>
      </div>
      <div flex text-neutral-3 gap-3 w-100 justify-end mr-30>
        <i class="i-carbon:logo-facebook" text-lg />
        <i class="i-carbon:logo-twitter" text-lg />
        <i class="i-carbon:logo-instagram" text-lg />
      </div>
    </div>
  </div>
</template>
