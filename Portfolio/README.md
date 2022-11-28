# ASSIGNMENT #09: Portfolio

##### _By Vicky Jen| DH110: User Experience and Design_

1. Heuristic Evaluation: https://github.com/vickyjen/DH110-22F-Vicky/tree/main/ASSIGNMENT01
2. Usability Testing: https://github.com/vickyjen/DH110-22F-Vicky/tree/main/ASSIGNMENT02
3. Contextual Inquiry: https://github.com/vickyjen/DH110-22F-Vicky/tree/main/ASSIGNMENT03
4. User Persona/Scenario: https://github.com/vickyjen/DH110-22F-Vicky/tree/main/ASSIGNMENT04
5. Lo-fi Prototype: https://github.com/vickyjen/DH110-22F-Vicky/tree/main/ASSIGNMENT%2005
6. Interface Design: https://github.com/vickyjen/DH110-22F-Vicky/tree/main/ASSIGNMENT06
7. Hi-Fi Prototype: https://github.com/vickyjen/DH110-22F-Vicky/tree/main/ASSIGNMENT07

import React from 'react'

import DangerousHTML from 'dangerous-html/react'

import Navbar from './navbar'
import Mark from './mark'
import Card from './card'
import Accordion from './accordion'
import Includes from './includes'
import Excludes from './excludes'
import Review from './review'
import Article from './article'
import FAQ from './f-a-q'
import projectStyles from '.style.module.css'
import styles from './home.module.css'

const Home = (props) => {
  return (
    <div className={styles['container']}>
      <Navbar rootClassName="root-class-name"></Navbar>
      <section className={styles['section']}>
        <div className={styles['hero']}>
          <div className={styles['content']}>
            <main className={styles['main']}>
              <header className={styles['header']}>
                <h1 className={styles['heading']}>
                  <span>
                    Surf Up with
                    <span
                      dangerouslySetInnerHTML={{
                        __html: ' ',
                      }}
                    />
                  </span>
                  <br></br>
                  <span>YEW!</span>
                </h1>
                <span className={styles['caption']}>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                  do eiusmod tempor incididunt.
                </span>
              </header>
              <div className={styles['buttons']}>
                <div
                  className={` ${styles['get-started']} ${projectStyles['button']} `}
                >
                  <span className={styles['text03']}>Get started</span>
                </div>
                <div
                  className={` ${styles['get-started1']} ${projectStyles['button']} `}
                >
                  <span className={styles['text04']}>View features</span>
                </div>
              </div>
            </main>
            <div className={styles['highlight']}>
              <div className={styles['avatars']}>
                <img
                  alt="image"
                  src="https://images.unsplash.com/photo-1552234994-66ba234fd567?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDN8fHBvdHJhaXR8ZW58MHx8fHwxNjY3MjQ0ODcx&amp;ixlib=rb-4.0.3&amp;w=200"
                  className={` ${styles['image']} ${projectStyles['avatar']} `}
                />
                <img
                  alt="image"
                  src="https://images.unsplash.com/photo-1610276198568-eb6d0ff53e48?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDF8fHBvdHJhaXR8ZW58MHx8fHwxNjY3MjQ0ODcx&amp;ixlib=rb-4.0.3&amp;w=200"
                  className={` ${styles['image01']} ${projectStyles['avatar']} `}
                />
                <img
                  alt="image"
                  src="https://images.unsplash.com/photo-1618151313441-bc79b11e5090?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDEzfHxwb3RyYWl0fGVufDB8fHx8MTY2NzI0NDg3MQ&amp;ixlib=rb-4.0.3&amp;w=200"
                  className={` ${styles['image02']} ${projectStyles['avatar']} `}
                />
              </div>
              <label className={styles['caption1']}>
                Loved by 10,000+ people like you.
              </label>
            </div>
          </div>
          <div className={styles['image03']}>
            <img
              alt="image"
              src="/playground_assets/heroimage-1500h.png"
              className={styles['image04']}
            />
          </div>
          <div className={styles['image05']}>
            <img
              alt="image"
              src="/playground_assets/heroimage-1500h.png"
              className={styles['image06']}
            />
          </div>
        </div>
      </section>
      <section className={styles['section01']}>
        <h2 className={styles['text05']}>
          Our doctors and therapists are here, 24/7.
        </h2>
        <div className={styles['features']}>
          <header
            className={` ${projectStyles['feature']} ${projectStyles['feature-active']} ${styles['feature']} `}
          >
            <h3 className={styles['text06']}>Urgent Care</h3>
            <p className={styles['text07']}>Doloremque laudantium</p>
          </header>
          <header
            className={` ${projectStyles['feature']} ${styles['feature1']} `}
          >
            <h3 className={styles['text08']}>Chronic Care</h3>
            <p className={styles['text09']}>Doloremque laudantium</p>
          </header>
          <header
            className={` ${projectStyles['feature']} ${styles['feature2']} `}
          >
            <h3 className={styles['text10']}>Mental Health</h3>
            <p className={styles['text11']}>Doloremque laudantium</p>
          </header>
        </div>
        <div className={styles['note']}>
          <div className={styles['content1']}>
            <main className={styles['main1']}>
              <h2 className={styles['heading01']}>
                Accessing this Medicare benefit is easy
              </h2>
              <p className={styles['paragraph']}>
                <span>
                  Sed ut perspiciatis unde omnis iste natus error sit voluptatem
                  accusantium doloremque laudantium, totam rem aperiam, eaque
                  ipsa quae ab illo inventore veritatis et quasi architecto
                  beatae.
                </span>
                <br></br>
                <br></br>
                <span>
                  Doloremque laudantium, totam rem aperiam, eaque ipsa quae ab
                  illo inventore veritatis et quasi architecto beatae.
                </span>
                <br></br>
              </p>
            </main>
            <div className={styles['explore-more']}>
              <p className={styles['text17']}>Explore more -&gt;</p>
            </div>
          </div>
          <div className={styles['image07']}>
            <img
              alt="image"
              src="/playground_assets/group%201490-1200w.png"
              className={styles['image08']}
            />
          </div>
        </div>
      </section>
      <section className={styles['section02']}>
        <header className={styles['header01']}>
          <h2 className={styles['text18']}>
            Why do you need a mobile medical app?
          </h2>
          <span className={styles['text19']}>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt.
          </span>
        </header>
        <section className={styles['note1']}>
          <div className={styles['image09']}>
            <img
              alt="image"
              src="/playground_assets/group%201428-1200w.png"
              className={styles['image10']}
            />
          </div>
          <div className={styles['content2']}>
            <div className={styles['main2']}>
              <div className={styles['caption2']}>
                <span className={projectStyles['section-head']}>
                  Tempor incididunt
                </span>
              </div>
              <div className={styles['heading02']}>
                <h2 className={projectStyles['section-heading']}>
                  We provide compassionate care from start to finish.
                </h2>
                <p className={projectStyles['section-description']}>
                  Sed ut perspiciatis unde omnis iste natus error sit voluptatem
                  accusantium doloremque laudantium, totam rem aperiam, eaque
                  ipsa quae ab illo inventore veritatis et quasi architecto
                  beatae.
                </p>
              </div>
            </div>
            <div
              className={` ${styles['get-started2']} ${projectStyles['button']} `}
            >
              <span className={styles['text20']}>Get started</span>
            </div>
          </div>
        </section>
        <section className={styles['note2']}>
          <div className={styles['image11']}>
            <img
              alt="image"
              src="/playground_assets/group%201449-1200w.png"
              className={styles['image12']}
            />
          </div>
          <div className={styles['content3']}>
            <main className={styles['main3']}>
              <header className={styles['caption3']}>
                <span
                  className={` ${styles['section04']} ${projectStyles['section-head']} `}
                >
                  Tempor incididunt
                </span>
              </header>
              <main className={styles['heading04']}>
                <header className={styles['header02']}>
                  <h2 className={projectStyles['section-heading']}>
                    Great care, wherever you are
                  </h2>
                  <p className={projectStyles['section-description']}>
                    Sed ut perspiciatis unde omnis iste natus error sit
                    voluptatem accusantium doloremque laudantium.
                  </p>
                </header>
                <div className={styles['checkmarks']}>
                  <Mark></Mark>
                  <Mark Label="Quis nostrud exercitation ullamco"></Mark>
                  <Mark Label="Reprehenderit qui in ea voluptate velit"></Mark>
                </div>
              </main>
            </main>
            <div
              className={` ${styles['get-started3']} ${projectStyles['button']} `}
            >
              <span className={styles['text21']}>Get started</span>
            </div>
          </div>
        </section>
      </section>
      <section className={styles['section05']}>
        <header className={styles['header03']}>
          <header className={styles['left']}>
            <span className={projectStyles['section-head']}>
              Tempor incididunt
            </span>
            <h2 className={projectStyles['section-heading']}>
              <span>Meet our network</span>
              <br></br>
              <span>of licensed providers</span>
            </h2>
          </header>
          <div className={styles['right']}>
            <p
              className={` ${styles['paragraph3']} ${projectStyles['section-description']} `}
            >
              Sed ut perspiciatis unde omnis iste natus error sit voluptatem
              accusantium doloremque laudantium, totam rem aperiam.
            </p>
          </div>
        </header>
        <main className={styles['cards']}>
          <Card rootClassName="root-class-name"></Card>
          <Card
            Icon="/playground_assets/group%201314-200h.png"
            rootClassName="root-class-name1"
          ></Card>
          <Card
            Icon="/playground_assets/group%201317-200h.png"
            rootClassName="root-class-name2"
          ></Card>
        </main>
      </section>
      <section className={styles['section07']}>
        <div className={styles['note3']}>
          <div className={styles['image13']}>
            <img
              alt="image"
              src="/playground_assets/iphone%2014%20pro%20max-1200w.png"
              className={styles['image14']}
            />
          </div>
          <div className={styles['content4']}>
            <div className={styles['caption4']}>
              <span className={projectStyles['section-head']}>
                Tempor incididunt
              </span>
            </div>
            <div className={styles['heading07']}>
              <div className={styles['header04']}>
                <h2 className={projectStyles['section-heading']}>
                  Tips to get care, answers and advice faster
                </h2>
              </div>
              <Accordion rootClassName="root-class-name"></Accordion>
            </div>
          </div>
        </div>
      </section>
      <section className={styles['section09']}>
        <div className={styles['cube']}>
          <div className={` ${styles['top']} ${projectStyles['side']} `}></div>
          <div
            className={` ${styles['front']} ${projectStyles['side']} `}
          ></div>
          <div
            className={` ${styles['left1']} ${projectStyles['side']} `}
          ></div>
        </div>
        <main className={styles['banner']}>
          <div className={styles['header05']}>
            <h2 className={projectStyles['section-heading']}>
              Planical makes online doctor visits easier
            </h2>
            <p
              className={` ${styles['description']} ${projectStyles['section-description']} `}
            >
              Lorem ipsum dolor sit amet!
            </p>
          </div>
          <div className={styles['buttons1']}>
            <div
              className={` ${styles['get-started4']} ${projectStyles['button']} `}
            >
              <span className={styles['text25']}>Get started</span>
            </div>
            <div
              className={` ${styles['book-demo']} ${projectStyles['button']} `}
            >
              <span className={styles['text26']}>Book a demo</span>
            </div>
          </div>
        </main>
      </section>
      <section className={styles['section10']}>
        <div className={styles['cube1']}>
          <div className={` ${styles['top1']} ${projectStyles['side']} `}></div>
          <div
            className={` ${styles['front1']} ${projectStyles['side']} `}
          ></div>
          <div
            className={` ${styles['left2']} ${projectStyles['side']} `}
          ></div>
        </div>
        <main className={styles['pricing']}>
          <header className={styles['header06']}>
            <header className={styles['left3']}>
              <span className={projectStyles['section-head']}>Pricing</span>
              <h2
                className={` ${projectStyles['section-heading']} ${styles['heading10']} `}
              >
                Start small, think big
              </h2>
            </header>
            <div className={styles['right1']}>
              <p
                className={` ${styles['paragraph4']} ${projectStyles['section-description']} `}
              >
                Sed ut perspiciatis unde omnis iste natus error sit voluptatem
                accusantium doloremque laudantium, totam rem aperiam.
              </p>
            </div>
          </header>
          <div className={styles['plans-container']}>
            <div className={styles['switch']}>
              <div className={projectStyles['switch']}>
                <label className={styles['text27']}>Monthly</label>
              </div>
              <div
                className={` ${styles['switch2']} ${projectStyles['switch']} `}
              >
                <label className={styles['text28']}>Yearly</label>
              </div>
            </div>
            <main className={styles['plans']}>
              <div className={styles['plan']}>
                <div className={styles['details']}>
                  <div className={styles['header07']}>
                    <label className={styles['name']}>Basic</label>
                    <div className={styles['pricing1']}>
                      <h1 className={styles['price']}>$9</h1>
                      <span className={styles['duration']}>/mo</span>
                    </div>
                  </div>
                  <p className={styles['description1']}>
                    Good for sed quia consequuntur magni dolores eos qui
                    ratione.
                  </p>
                </div>
                <div className={styles['buy-details']}>
                  <div
                    className={` ${styles['buy']} ${projectStyles['button']} `}
                  >
                    <span className={styles['text29']}>
                      <span>Start Basic</span>
                      <br></br>
                    </span>
                  </div>
                  <div className={styles['features1']}>
                    <span className={styles['heading11']}>You will get</span>
                    <div className={styles['list']}>
                      <Includes rootClassName="root-class-name"></Includes>
                      <Includes rootClassName="root-class-name"></Includes>
                      <Includes rootClassName="root-class-name"></Includes>
                      <Includes rootClassName="root-class-name"></Includes>
                      <Excludes rootClassName="root-class-name"></Excludes>
                      <Excludes rootClassName="root-class-name"></Excludes>
                      <Excludes rootClassName="root-class-name"></Excludes>
                      <Excludes rootClassName="root-class-name"></Excludes>
                      <Excludes rootClassName="root-class-name"></Excludes>
                      <Excludes rootClassName="root-class-name"></Excludes>
                    </div>
                  </div>
                </div>
              </div>
              <div className={styles['plan1']}>
                <div className={styles['details1']}>
                  <div className={styles['header08']}>
                    <label className={styles['name1']}>Professional</label>
                    <div className={styles['pricing2']}>
                      <h1 className={styles['price1']}>$15</h1>
                      <span className={styles['duration1']}>/mo</span>
                    </div>
                  </div>
                  <p className={styles['description2']}>
                    Good for sed quia consequuntur magni dolores eos qui
                    ratione.
                  </p>
                </div>
                <div className={styles['buy-details1']}>
                  <div
                    className={` ${styles['buy1']} ${projectStyles['button']} `}
                  >
                    <span className={styles['text32']}>
                      <span>Start Professional</span>
                      <br></br>
                    </span>
                  </div>
                  <div className={styles['features2']}>
                    <span className={styles['heading12']}>You will get</span>
                    <div className={styles['list1']}>
                      <Includes rootClassName="root-class-name"></Includes>
                      <Includes rootClassName="root-class-name"></Includes>
                      <Includes rootClassName="root-class-name"></Includes>
                      <Includes rootClassName="root-class-name"></Includes>
                      <Includes rootClassName="root-class-name"></Includes>
                      <Includes rootClassName="root-class-name"></Includes>
                      <Includes rootClassName="root-class-name"></Includes>
                      <Excludes rootClassName="root-class-name"></Excludes>
                      <Excludes rootClassName="root-class-name"></Excludes>
                      <Excludes rootClassName="root-class-name"></Excludes>
                    </div>
                  </div>
                </div>
              </div>
              <div className={styles['plan2']}>
                <div className={styles['details2']}>
                  <div className={styles['header09']}>
                    <label className={styles['name2']}>Enterprise</label>
                    <div className={styles['pricing3']}>
                      <span className={styles['price2']}>$99</span>
                      <span className={styles['duration2']}>/mo</span>
                    </div>
                  </div>
                  <p className={styles['description3']}>
                    Good for sed quia consequuntur magni dolores eos qui
                    ratione.
                  </p>
                </div>
                <div className={styles['buy-details2']}>
                  <div
                    className={` ${styles['buy2']} ${projectStyles['button']} `}
                  >
                    <span className={styles['text35']}>
                      <span>Start Enterprise</span>
                      <br></br>
                    </span>
                  </div>
                  <div className={styles['features3']}>
                    <span className={styles['heading13']}>You will get</span>
                    <div className={styles['list2']}>
                      <Includes rootClassName="root-class-name"></Includes>
                      <Includes rootClassName="root-class-name"></Includes>
                      <Includes rootClassName="root-class-name"></Includes>
                      <Includes rootClassName="root-class-name"></Includes>
                      <Includes rootClassName="root-class-name"></Includes>
                      <Includes rootClassName="root-class-name"></Includes>
                      <Includes rootClassName="root-class-name"></Includes>
                      <Includes rootClassName="root-class-name"></Includes>
                      <Includes rootClassName="root-class-name"></Includes>
                      <Includes rootClassName="root-class-name"></Includes>
                    </div>
                  </div>
                </div>
              </div>
            </main>
          </div>
        </main>
        <div className={styles['help']}>
          <span className={styles['text38']}>
            <span>Need any help?</span>
            <br></br>
          </span>
          <div className={styles['contact-support']}>
            <p className={styles['text41']}>Contact support -&gt;</p>
          </div>
        </div>
      </section>
      <section className={styles['section12']}>
        <header className={styles['header10']}>
          <header className={styles['left4']}>
            <span className={projectStyles['section-head']}>
              Tempor incididunt
            </span>
            <h2
              className={` ${styles['heading14']} ${projectStyles['section-heading']} `}
            >
              What users say about us
            </h2>
          </header>
          <div className={styles['right2']}>
            <p
              className={` ${styles['paragraph5']} ${projectStyles['section-description']} `}
            >
              Sed ut perspiciatis unde omnis iste natus error sit voluptatem
              accusantium doloremque laudantium, totam rem aperiam.
            </p>
          </div>
        </header>
        <main className={styles['cards1']}>
          <div className={styles['container1']}>
            <Review rootClassName="root-class-name"></Review>
            <Review
              Quote="“Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur.\u2028\u2028Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur.”"
              rootClassName="root-class-name"
            ></Review>
          </div>
          <div className={styles['container2']}>
            <Review
              Quote="“Illum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.”"
              rootClassName="root-class-name"
            ></Review>
            <Review
              Quote="“Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.”"
              rootClassName="root-class-name"
            ></Review>
          </div>
          <div className={styles['container3']}>
            <Review
              Quote="“Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae.”"
              rootClassName="root-class-name"
            ></Review>
            <Review
              Quote="“Doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae.”"
              rootClassName="root-class-name"
            ></Review>
          </div>
        </main>
        <div className={styles['view-more']}>
          <p className={styles['text42']}>View more</p>
        </div>
      </section>
      <section className={styles['section14']}>
        <header className={styles['header11']}>
          <span className={projectStyles['section-head']}>
            Articles about us
          </span>
          <h2
            className={` ${styles['heading15']} ${projectStyles['section-heading']} `}
          >
            We’re the app on everyone’s lips
          </h2>
        </header>
        <main className={styles['cards2']}>
          <Article rootClassName="root-class-name"></Article>
          <Article
            Header="techeu"
            SpecialHeader="eu"
            rootClassName="root-class-name"
          ></Article>
          <Article Header="sifted/" rootClassName="root-class-name"></Article>
        </main>
      </section>
      <section className={styles['section16']}>
        <header className={styles['header12']}>
          <span className={projectStyles['section-head']}>FAQ</span>
          <h2
            className={` ${styles['heading16']} ${projectStyles['section-heading']} `}
          >
            Frequently asked questions
          </h2>
        </header>
        <main className={styles['accordion']}>
          <FAQ rootClassName="root-class-name"></FAQ>
        </main>
      </section>
      <section className={styles['section18']}>
        <main className={styles['content5']}>
          <header className={styles['header13']}>
            <h2
              className={` ${styles['heading17']} ${projectStyles['section-heading']} `}
            >
              Stop searching online for medications and use Planical app!
            </h2>
            <div className={styles['buttons2']}>
              <div
                className={` ${styles['i-o-s']} ${projectStyles['button']} `}
              >
                <img
                  alt="image"
                  src="/playground_assets/apple-200w.png"
                  className={styles['icon']}
                />
                <span className={styles['text43']}>Download for iOS</span>
              </div>
              <div
                className={` ${styles['android']} ${projectStyles['button']} `}
              >
                <img
                  alt="image"
                  src="/playground_assets/android-200h.png"
                  className={styles['icon1']}
                />
                <span className={styles['text44']}>Download for Android</span>
              </div>
            </div>
          </header>
          <img
            alt="image"
            src="/playground_assets/group%201505-1200w.png"
            className={styles['image15']}
          />
        </main>
      </section>
      <footer className={styles['footer']}>
        <div className={styles['content6']}>
          <main className={styles['main-content']}>
            <div className={styles['content7']}>
              <header className={styles['main4']}>
                <div className={styles['header14']}>
                  <img
                    alt="image"
                    src="/playground_assets/planical7012-ttpb.svg"
                    className={styles['branding']}
                  />
                  <span className={styles['text45']}>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  </span>
                </div>
                <div className={styles['socials']}>
                  <a
                    href="https://example.com"
                    target="_blank"
                    rel="noreferrer noopener"
                    className={styles['link']}
                  >
                    <img
                      alt="image"
                      src="/playground_assets/linkedin-200h.png"
                      className={projectStyles['social']}
                    />
                  </a>
                  <a
                    href="https://example.com"
                    target="_blank"
                    rel="noreferrer noopener"
                    className={styles['link1']}
                  >
                    <img
                      alt="image"
                      src="/playground_assets/instagram-200h.png"
                      className={projectStyles['social']}
                    />
                  </a>
                  <a
                    href="https://example.com"
                    target="_blank"
                    rel="noreferrer noopener"
                    className={styles['link2']}
                  >
                    <img
                      alt="image"
                      src="/playground_assets/twitter-200h.png"
                      className={projectStyles['social']}
                    />
                  </a>
                </div>
              </header>
              <header className={styles['categories']}>
                <div className={styles['category']}>
                  <div className={styles['header15']}>
                    <span className={projectStyles['footer-header']}>
                      Solutions
                    </span>
                  </div>
                  <div className={styles['links']}>
                    <span className={projectStyles['footer-link']}>
                      Responsive Web Design
                    </span>
                    <span className={projectStyles['footer-link']}>
                      Responsive Prototypes
                    </span>
                    <span className={projectStyles['footer-link']}>
                      Design to Code
                    </span>
                    <span className={projectStyles['footer-link']}>
                      Static Website Builder
                    </span>
                    <span className={projectStyles['footer-link']}>
                      Static Website Generator
                    </span>
                  </div>
                </div>
                <div className={styles['category1']}>
                  <div className={styles['header16']}>
                    <span className={projectStyles['footer-header']}>
                      Company
                    </span>
                  </div>
                  <div className={styles['links1']}>
                    <span className={projectStyles['footer-link']}>About</span>
                    <span className={projectStyles['footer-link']}>Team</span>
                    <span className={projectStyles['footer-link']}>News</span>
                    <span className={projectStyles['footer-link']}>
                      Partners
                    </span>
                    <span className={projectStyles['footer-link']}>
                      Careers
                    </span>
                    <span className={projectStyles['footer-link']}>
                      Press &amp; Media
                    </span>
                  </div>
                </div>
              </header>
            </div>
            <section className={styles['copyright']}>
              <span className={styles['text59']}>
                © 2022 latitude. All Rights Reserved.
              </span>
            </section>
          </main>
          <main className={styles['subscribe']}>
            <main className={styles['main5']}>
              <h1 className={styles['heading18']}>
                Subscribe to our newsletter
              </h1>
              <div className={styles['input-field']}>
                <input
                  type="email"
                  placeholder="Enter your email"
                  className={` ${styles['textinput']} ${projectStyles['input']} `}
                />
                <div
                  className={` ${styles['buy3']} ${projectStyles['button']} `}
                >
                  <span className={styles['text60']}>-&gt;</span>
                  <span className={styles['text61']}>
                    <span>Subscribe now</span>
                    <br></br>
                  </span>
                </div>
              </div>
            </main>
            <h1 className={styles['notice']}>
              By subscribing to our newsletter you agree with our Terms and
              Conditions.
            </h1>
          </main>
          <section className={styles['copyright1']}>
            <span className={styles['text64']}>
              © 2022 latitude. All Rights Reserved.
            </span>
          </section>
        </div>
      </footer>
      <div>
        <DangerousHTML
          html={`<script>
    /*
Accordion - Code Embed
*/

/* listenForUrlChangesAccordion() makes sure that if you changes pages inside your app,
the Accordions will still work*/

const listenForUrlChangesAccordion = () => {
      let url = location.href;
      document.body.addEventListener(
        "click",
        () => {
          requestAnimationFrame(() => {
            if (url !== location.href) {
              runAccordionCodeEmbed();
              url = location.href;
            }
          });
        },
        true
      );
    };


const runAccordionCodeEmbed = () => {
    const accordionContainers = document.querySelectorAll('[data-role="accordion-container"]'); // All accordion containers
    const accordionContents = document.querySelectorAll('[data-role="accordion-content"]'); // All accordion content
    const accordionIcons = document.querySelectorAll('[data-role="accordion-icon"]'); // All accordion icons

    accordionContents.forEach((accordionContent) => {
        accordionContent.style.display = "none"; //Hides all accordion contents
    });

    accordionContainers.forEach((accordionContainer, index) => {
        accordionContainer.addEventListener("click", () => {
            accordionContents.forEach((accordionContent) => {
            accordionContent.style.display = "none"; //Hides all accordion contents
            });

            accordionIcons.forEach((accordionIcon) => {
                accordionIcon.style.transform = "rotate(0deg)"; // Resets all icon transforms to 0deg (default)
            });

            accordionContents[index].style.display = "flex"; // Shows accordion content
            accordionIcons[index].style.transform = "rotate(180deg)"; // Rotates accordion icon 180deg
        });
    });
}

runAccordionCodeEmbed()
listenForUrlChangesAccordion()

/*
Here's what the above is doing:
    1. Selects all accordion containers, contents, and icons
    2. Hides all accordion contents
    3. Adds an event listener to each accordion container
    4. When an accordion container is clicked, it:
        - Hides all accordion contents
        - Resets all icon transforms to 0deg (default)
        - Checks if this container has class "accordion-open"
            - If it does, it removes class "accordion-open"
            - If it doesn't, it:
                - Removes class "accordion-open" from all containers
                - Adds class "accordion-open" to this container
                - Shows accordion content
                - Rotates accordion icon 180deg
*/
</script>`}
        ></DangerousHTML>
      </div>
    </div>
  )
}

export default Home
