# CSS ASSIGNMENT
## DRIBBLE WEBPAGE
## HTML code:
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble - Discover the World's Top Designer & Creative Professionals</title>
    <script src="https://kit.fontawesome.com/18e54117ba.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="style.css">
    <link rel="shortcut icon" href="./images/favicon.png" type="image/x-icon">
    <link rel="stylesheet" href="responsive.css">
</head>

<body>
    <main>
        <div class="heroContainer">
            <nav>

                <div class="links">
                    <i class="fa-solid fa-bars-staggered"></i>
                    <img src="./images/Dribbble-Logo.png" alt="">
                    <a href="#">Find talent</a>
                    <a href="#">Inspiration</a>
                    <a href="#">Learn design<i class="fa-solid fa-caret-down"></i></a>
                    <a href="#">Jobs</a>
                    <a href="#">Go Pro</a>
                </div>
                <div class="signUps">
                    <input type="text" name="search" placeholder=" 🔍 Search..">
                    <button id="Login" type="button">Log in</button>
                    <button type="button" id="signIn">Sign up</button>
                </div>
            </nav>
            <div class="hero">
                <h2>Over 3 million ready-to-work creatives!</h2>
                <h1>The world's destination <br>for design</h1>
                <p>Get inspired by the works of millions of top-rated designers & agencies around the world/</p>
                <button id="signIn">Get started</button>
            </div>
        </div>
        <div class="scrollerContainer">
            <div class="scroller">
                <div class="elem">
                    <img src="https://cdn.dribbble.com/uploads/47170/original/cd3266dde4f00a5d6a509c7375ddaecd.png?1685644840&format=webp&resize=400x498&vertical=center"
                        alt="">
                    <div class="overlay">
                        <p>Lucas Miller</p>
                        <p>Backend Developer</p>
                        <div>

                            <span>Node.JS</span>
                            <span>MongoDB</span>
                        </div>
                    </div>
                </div>
                <div class="elem">
                    <video
                        src="https://cdn.dribbble.com/uploads/47181/original/1e3a73a174484bef522b620c401cd00a.mp4?1685645427"
                        autoplay loop muted></video>
                    <div class="overlay">
                        <p>Emma Smith</p>
                        <p>Frontend Developer</p>
                        <div>
                            <span>Web dev</span>
                            <span>UI/UX</span>
                        </div>
                    </div>
                </div>
                <div class="elem">
                    <img src="https://cdn.dribbble.com/uploads/47172/original/d85ae8c7db2421e9a01ecac942978d4b.png?1685645079&format=webp&resize=400x498&vertical=center"
                        alt="">
                    <div class="overlay">
                        <p>Grace Taylor</p>
                        <p>Full Stack Developer</p>
                        <div>
                            <span>React.JS</span>
                            <span>MongoDB</span>
                        </div>
                    </div>
                </div>
                <div class="elem">
                    <img src="https://cdn.dribbble.com/uploads/47175/original/1fb34610061a95a007ac5e7b1dc53138.jpeg?1685645183&format=webp&resize=400x498&vertical=center"
                        alt="">
                    <div class="overlay">
                        <p>Ethan Clark</p>
                        <p>Mobile App Developer</p>
                        <div>
                            <span>React Native</span>
                            <span>MongoDB</span>
                        </div>
                    </div>
                </div>
                <div class="elem">
                    <img src="https://cdn.dribbble.com/uploads/47176/original/9b22cd83bde1809976bec0722d1f8923.jpeg?1685645213&format=webp&resize=400x498&vertical=center"
                        alt="">
                    <div class="overlay">
                        <p>Lily Cooper</p>
                        <p>Web Developer</p>
                        <div>
                            <span>React.JS</span>
                            <span>MongoDB</span>
                        </div>
                    </div>
                </div>
                <div class="elem">
                    <video
                        src="https://cdn.dribbble.com/uploads/47180/original/1def7b9fb30832c4af4353b325d9c3af.mp4?1685645402"
                        autoplay loop muted></video>
                    <div class="overlay">
                        <p>Owen Davis</p>
                        <p>DevOps Engineer</p>
                        <div>
                            <span>DevOPS</span>
                            <span>MERN</span>
                        </div>
                    </div>
                </div>
                <div class="elem">
                    <img src="https://cdn.dribbble.com/uploads/47178/original/mercedes-bazan.png?1689174566&format=webp&resize=400x498&vertical=center"
                        alt="">
                    <div class="overlay">
                        <p>Stella Brown</p>
                        <p>Data Scientist</p>
                        <div>
                            <span>Data Scientist</span>
                        </div>
                    </div>
                </div>
                <div class="elem">
                    <img src="https://cdn.dribbble.com/uploads/47173/original/Vladimir_Gruev.png?1689174896&format=webp&resize=400x498&vertical=center"
                        alt="">
                    <div class="overlay">
                        <p>Stella Brown</p>
                        <p>Data Scientist</p>
                        <div>
                            <span>Data Scientist</span>
                        </div>
                    </div>
                </div>
                <div class="elem">
                    <video
                        src="https://cdn.dribbble.com/uploads/47179/original/35d07cfebd303e05e688078015da0cc2.mp4?1685645373"
                        autoplay muted loop></video>
                    <div class="overlay">
                        <p>Caleb White</p>
                        <p>Machine Learning Engineer</p>
                        <div>
                            <span>Machine Learning</span>
                        </div>
                    </div>
                </div>
                <div class="elem">
                    <img src="https://cdn.dribbble.com/uploads/47174/original/4f02d72fe701b15b2168a4954332427f.png?1685645150&format=webp&resize=400x498&vertical=center"
                        alt="">
                    <div class="overlay">
                        <p>Mia Turner</p>
                        <p>Data Scientist</p>
                        <div>
                            <span>Data Scientist</span>
                        </div>
                    </div>
                </div>
                <div class="elem">
                    <img src="https://cdn.dribbble.com/uploads/47177/original/3986915be548424a5d36657f2b034ead.jpeg?1685645250&format=webp&resize=400x498&vertical=center"
                        alt="">
                    <div class="overlay">
                        <p>Noah Carter</p>
                        <p>Data Scientist</p>
                        <div>
                            <span>Data Scientist</span>
                        </div>
                    </div>
                </div>
            </div>
            <div class="scroller">
                <div class="elem">
                    <img src="https://cdn.dribbble.com/uploads/47170/original/cd3266dde4f00a5d6a509c7375ddaecd.png?1685644840&format=webp&resize=400x498&vertical=center"
                        alt="">
                    <div class="overlay">
                        <p>Lucas Miller</p>
                        <p>Backend Developer</p>
                        <div>

                            <span>Node.JS</span>
                            <span>MongoDB</span>
                        </div>
                    </div>
                </div>
                <div class="elem">
                    <video
                        src="https://cdn.dribbble.com/uploads/47181/original/1e3a73a174484bef522b620c401cd00a.mp4?1685645427"
                        autoplay loop muted></video>
                    <div class="overlay">
                        <p>Emma Smith</p>
                        <p>Frontend Developer</p>
                        <div>
                            <span>Web dev</span>
                            <span>UI/UX</span>
                        </div>
                    </div>
                </div>
                <div class="elem">
                    <img src="https://cdn.dribbble.com/uploads/47172/original/d85ae8c7db2421e9a01ecac942978d4b.png?1685645079&format=webp&resize=400x498&vertical=center"
                        alt="">
                    <div class="overlay">
                        <p>Grace Taylor</p>
                        <p>Full Stack Developer</p>
                        <div>
                            <span>React.JS</span>
                            <span>MongoDB</span>
                        </div>
                    </div>
                </div>
                <div class="elem">
                    <img src="https://cdn.dribbble.com/uploads/47175/original/1fb34610061a95a007ac5e7b1dc53138.jpeg?1685645183&format=webp&resize=400x498&vertical=center"
                        alt="">
                    <div class="overlay">
                        <p>Ethan Clark</p>
                        <p>Mobile App Developer</p>
                        <div>
                            <span>React Native</span>
                            <span>MongoDB</span>
                        </div>
                    </div>
                </div>
                <div class="elem">
                    <img src="https://cdn.dribbble.com/uploads/47176/original/9b22cd83bde1809976bec0722d1f8923.jpeg?1685645213&format=webp&resize=400x498&vertical=center"
                        alt="">
                    <div class="overlay">
                        <p>Lily Cooper</p>
                        <p>Web Developer</p>
                        <div>
                            <span>React.JS</span>
                            <span>MongoDB</span>
                        </div>
                    </div>
                </div>
                <div class="elem">
                    <video
                        src="https://cdn.dribbble.com/uploads/47180/original/1def7b9fb30832c4af4353b325d9c3af.mp4?1685645402"
                        autoplay loop muted></video>
                    <div class="overlay">
                        <p>Owen Davis</p>
                        <p>DevOps Engineer</p>
                        <div>
                            <span>DevOPS</span>
                            <span>MERN</span>
                        </div>
                    </div>
                </div>
                <div class="elem">
                    <img src="https://cdn.dribbble.com/uploads/47178/original/mercedes-bazan.png?1689174566&format=webp&resize=400x498&vertical=center"
                        alt="">
                    <div class="overlay">
                        <p>Stella Brown</p>
                        <p>Data Scientist</p>
                        <div>
                            <span>Data Scientist</span>
                        </div>
                    </div>
                </div>
                <div class="elem">
                    <img src="https://cdn.dribbble.com/uploads/47173/original/Vladimir_Gruev.png?1689174896&format=webp&resize=400x498&vertical=center"
                        alt="">
                    <div class="overlay">
                        <p>Stella Brown</p>
                        <p>Data Scientist</p>
                        <div>
                            <span>Data Scientist</span>
                        </div>
                    </div>
                </div>
                <div class="elem">
                    <video
                        src="https://cdn.dribbble.com/uploads/47179/original/35d07cfebd303e05e688078015da0cc2.mp4?1685645373"
                        autoplay muted loop></video>
                    <div class="overlay">
                        <p>Caleb White</p>
                        <p>Machine Learning Engineer</p>
                        <div>
                            <span>Machine Learning</span>
                        </div>
                    </div>
                </div>
                <div class="elem">
                    <img src="https://cdn.dribbble.com/uploads/47174/original/4f02d72fe701b15b2168a4954332427f.png?1685645150&format=webp&resize=400x498&vertical=center"
                        alt="">
                    <div class="overlay">
                        <p>Mia Turner</p>
                        <p>Data Scientist</p>
                        <div>
                            <span>Data Scientist</span>
                        </div>
                    </div>
                </div>
                <div class="elem">
                    <img src="https://cdn.dribbble.com/uploads/47177/original/3986915be548424a5d36657f2b034ead.jpeg?1685645250&format=webp&resize=400x498&vertical=center"
                        alt="">
                    <div class="overlay">
                        <p>Noah Carter</p>
                        <p>Data Scientist</p>
                        <div>
                            <span>Data Scientist</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <section>
            <h2>Explore inspiring designs</h2>
            <div>
                <div class="box">
                    <div class="boxImg">
                        <img src="https://cdn.dribbble.com/userupload/12604447/file/original-200d5d9fac56ed748042617f9c182d82.jpg?crop=102x0-1542x1080&resize=450x338&vertical=center"
                            alt="">
                        <div class="hover">
                            <h6>Characters for the new</h6>
                            <div>

                                <i class="fa-regular fa-bookmark"></i>
                                <i class="fa-regular fa-heart"></i>
                            </div>
                        </div>
                    </div>
                    <div class="boxFooter">
                        <img src="https://cdn.dribbble.com/users/3113663/avatars/small/dcbf1db5e3d7b105ddad162aec88279d.jpg?1671115528"
                            alt="">
                        <p>OVCHARKA </p>
                        <span id="pro">PRO</span>
                        <i class="fa-solid fa-heart">180</i><i class="fa-solid fa-eye">50k</i>
                    </div>
                </div>
                <div class="box">
                    <div class="boxImg">
                        <img src="https://cdn.dribbble.com/userupload/12568133/file/original-b5e19805df0bf8d7b7691cf3cc1e36d4.gif"
                            alt="">
                        <div class="hover">
                            <h6>Cheifs Playoff Football</h6>
                            <div>

                                <i class="fa-regular fa-bookmark"></i>
                                <i class="fa-regular fa-heart"></i>
                            </div>
                        </div>
                    </div>
                    <div class="boxFooter">
                        <img src="https://cdn.dribbble.com/users/3113663/avatars/small/dcbf1db5e3d7b105ddad162aec88279d.jpg?1671115528"
                            alt="">
                        <p>Alex Anderson</p>
                        <span id="pro">PRO</span>
                        <i class="fa-solid fa-heart">120</i><i class="fa-solid fa-eye">155k</i>
                    </div>
                </div>
                <div class="box">
                    <div class="boxImg">
                        <img src="https://cdn.dribbble.com/userupload/12475995/file/original-1bc2b890201f0026e8ee4834cbed2fb3.jpg?resize=450x338&vertical=center"
                            alt="">
                        <div class="hover">
                            <h6>Flora</h6>
                            <div>

                                <i class="fa-regular fa-bookmark"></i>
                                <i class="fa-regular fa-heart"></i>
                            </div>
                        </div>
                    </div>
                    <div class="boxFooter">
                        <img src="https://cdn.dribbble.com/users/3113663/avatars/small/dcbf1db5e3d7b105ddad162aec88279d.jpg?1671115528"
                            alt="">
                        <p>Mari Maka</p>
                        <span id="pro">PRO</span>
                        <i class="fa-solid fa-heart">120</i><i class="fa-solid fa-eye">155k</i>
                    </div>
                </div>
                <div class="box">
                    <div class="boxImg">
                        <img src="https://cdn.dribbble.com/userupload/12645779/file/original-abab66ecf014bd1ad90d52fd06ec4ffb.jpg?resize=450x338&vertical=center"
                            alt="">
                        <div class="hover">
                            <h6>Sky turns pink.</h6>
                            <div>

                                <i class="fa-regular fa-bookmark"></i>
                                <i class="fa-regular fa-heart"></i>
                            </div>
                        </div>
                    </div>
                    <div class="boxFooter">
                        <img src="https://cdn.dribbble.com/users/3113663/avatars/small/dcbf1db5e3d7b105ddad162aec88279d.jpg?1671115528"
                            alt="">
                        <p>Sky turns pink.</p>
                        <span id="pro">PRO</span>
                        <i class="fa-solid fa-heart">800</i><i class="fa-solid fa-eye">5k</i>
                    </div>
                </div>
                <div class="box">
                    <div class="boxImg">
                        <img src="https://cdn.dribbble.com/userupload/12645350/file/original-df964776e74a551d4678fed4048bd1da.jpg?resize=450x338&vertical=center"
                            alt="">
                        <div class="hover">
                            <h6>Lost in thoughts</h6>
                            <div>

                                <i class="fa-regular fa-bookmark"></i>
                                <i class="fa-regular fa-heart"></i>
                            </div>
                        </div>
                    </div>
                    <div class="boxFooter">
                        <img src="https://cdn.dribbble.com/users/3113663/avatars/small/dcbf1db5e3d7b105ddad162aec88279d.jpg?1671115528"
                            alt="">
                        <p>Lost in thoughts</p>
                        <span id="pro">PRO</span>
                        <i class="fa-solid fa-heart">120</i><i class="fa-solid fa-eye">155k</i>
                    </div>
                </div>
                <div class="box">
                    <div class="boxImg">
                        <img src="https://cdn.dribbble.com/userupload/11972310/file/original-276cf5e95d09c15b0bed474499e2f933.jpg?resize=450x338&vertical=center"
                            alt="">
                        <div class="hover">
                            <h6>Raindrops dance silently.</h6>
                            <div>

                                <i class="fa-regular fa-bookmark"></i>
                                <i class="fa-regular fa-heart"></i>
                            </div>
                        </div>
                    </div>
                    <div class="boxFooter">
                        <img src="https://cdn.dribbble.com/users/3113663/avatars/small/dcbf1db5e3d7b105ddad162aec88279d.jpg?1671115528"
                            alt="">
                        <p>Raindrops dance silently.</p>
                        <span id="pro">PRO</span>
                        <i class="fa-solid fa-heart">120</i><i class="fa-solid fa-eye">155k</i>
                    </div>
                </div>
                <div class="box">
                    <div class="boxImg">
                        <img src="https://cdn.dribbble.com/userupload/12622359/file/original-c0f8e3e68413a8a7a05131d102073ee1.jpg?crop=0x0-808x606&resize=450x338&vertical=center"
                            alt="">
                        <div class="hover">
                            <h6>Chocolate tastes heavenly.</h6>
                            <div>

                                <i class="fa-regular fa-bookmark"></i>
                                <i class="fa-regular fa-heart"></i>
                            </div>
                        </div>
                    </div>
                    <div class="boxFooter">
                        <img src="https://cdn.dribbble.com/users/3113663/avatars/small/dcbf1db5e3d7b105ddad162aec88279d.jpg?1671115528"
                            alt="">
                        <p>Chocolate tastes heavenly.</p>
                        <span id="pro">PRO</span>
                        <i class="fa-solid fa-heart">120</i><i class="fa-solid fa-eye">155k</i>
                    </div>
                </div>
                <div class="box">
                    <div class="boxImg">
                        <img src="https://cdn.dribbble.com/userupload/12666604/file/original-4711c15d65a77ff95828d26b29781a8b.png?resize=450x338&vertical=center"
                            alt="">
                        <div class="hover">
                            <h6>Stars twinkle brightly.</h6>
                            <div>

                                <i class="fa-regular fa-bookmark"></i>
                                <i class="fa-regular fa-heart"></i>
                            </div>
                        </div>
                    </div>
                    <div class="boxFooter">
                        <img src="https://cdn.dribbble.com/users/3113663/avatars/small/dcbf1db5e3d7b105ddad162aec88279d.jpg?1671115528"
                            alt="">
                        <p>Stars twinkle</p>
                        <span id="pro">PRO</span>
                        <i class="fa-solid fa-heart">120</i><i class="fa-solid fa-eye">155k</i>
                    </div>
                </div>
                <div class="box">
                    <div class="boxImg">
                        <img src="https://cdn.dribbble.com/userupload/12623252/file/original-a244986587da0caf5bc6425f7a3ac8b0.jpg?resize=450x338&vertical=center"
                            alt="">
                        <div class="hover">
                            <h6>Ocean waves crash.</h6>
                            <div>

                                <i class="fa-regular fa-bookmark"></i>
                                <i class="fa-regular fa-heart"></i>
                            </div>
                        </div>
                    </div>
                    <div class="boxFooter">
                        <img src="https://cdn.dribbble.com/users/3113663/avatars/small/dcbf1db5e3d7b105ddad162aec88279d.jpg?1671115528"
                            alt="">
                        <p>Ocean waves crash.</p>
                        <span id="pro">PRO</span>
                        <i class="fa-solid fa-heart">120</i><i class="fa-solid fa-eye">155k</i>
                    </div>
                </div>
                <div class="box">
                    <div class="boxImg">
                        <img src="https://cdn.dribbble.com/userupload/12067422/file/original-51e29171c9abe410d2a84f9f41e4a345.jpg?crop=45x83-1962x1521&resize=450x338&vertical=center"
                            alt="">
                        <div class="hover">
                            <h6>Laughter echoes endlessly.</h6>
                            <div>

                                <i class="fa-regular fa-bookmark"></i>
                                <i class="fa-regular fa-heart"></i>
                            </div>
                        </div>
                    </div>
                    <div class="boxFooter">
                        <img src="https://cdn.dribbble.com/users/3113663/avatars/small/dcbf1db5e3d7b105ddad162aec88279d.jpg?1671115528"
                            alt="">
                        <p>Laughter echoes endlessly.</p>
                        <span id="pro">PRO</span>
                        <i class="fa-solid fa-heart">120</i><i class="fa-solid fa-eye">155k</i>
                    </div>
                </div>
                <div class="box">
                    <div class="boxImg">
                        <img src="https://cdn.dribbble.com/userupload/12660441/file/original-ae16536e2db2b562f3ba795f6dca3707.png?resize=450x338&vertical=center"
                            alt="">
                        <div class="hover">
                            <h6>Books transport minds.</h6>
                            <div>

                                <i class="fa-regular fa-bookmark"></i>
                                <i class="fa-regular fa-heart"></i>
                            </div>
                        </div>
                    </div>
                    <div class="boxFooter">
                        <img src="https://cdn.dribbble.com/users/3113663/avatars/small/dcbf1db5e3d7b105ddad162aec88279d.jpg?1671115528"
                            alt="">
                        <p>Books transport minds.</p>
                        <span id="pro">PRO</span>
                        <i class="fa-solid fa-heart">120</i><i class="fa-solid fa-eye">155k</i>
                    </div>
                </div>
                <div class="box">
                    <div class="boxImg">
                        <img src="https://cdn.dribbble.com/userupload/12677093/file/original-c6ec89d33298490d4f847b88bc955e1b.jpg?resize=450x338&vertical=center"
                            alt="">
                        <div class="hover">
                            <h6>Dreams shape reality.</h6>
                            <div>

                                <i class="fa-regular fa-bookmark"></i>
                                <i class="fa-regular fa-heart"></i>
                            </div>
                        </div>
                    </div>
                    <div class="boxFooter">
                        <img src="https://cdn.dribbble.com/users/3113663/avatars/small/dcbf1db5e3d7b105ddad162aec88279d.jpg?1671115528"
                            alt="">
                        <p>Dreams shape reality.</p>
                        <span id="pro">PRO</span>
                        <i class="fa-solid fa-heart">120</i><i class="fa-solid fa-eye">155k</i>
                    </div>
                </div>
                <div class="box">
                    <div class="boxImg">
                        <img src="https://cdn.dribbble.com/userupload/12662105/file/original-123b074356491c7901de62ef810f0f07.jpg?resize=450x338&vertical=center"
                            alt="">
                        <div class="hover">
                            <h6>Moonlight whispers </h6>
                            <div>

                                <i class="fa-regular fa-bookmark"></i>
                                <i class="fa-regular fa-heart"></i>
                            </div>
                        </div>
                    </div>
                    <div class="boxFooter">
                        <img src="https://cdn.dribbble.com/users/3113663/avatars/small/dcbf1db5e3d7b105ddad162aec88279d.jpg?1671115528"
                            alt="">
                        <p>Moonlight whispers.</p>
                        <span id="pro">PRO</span>
                        <i class="fa-solid fa-heart">120</i><i class="fa-solid fa-eye">155k</i>
                    </div>
                </div>
                <div class="box">
                    <div class="boxImg">
                        <img src="https://cdn.dribbble.com/userupload/12664085/file/original-0a9c7406360142c99d52d84f3bb99d0d.png?resize=450x338&vertical=center"
                            alt="">
                        <div class="hover">
                            <h6>Flowers bloom gracefully.</h6>
                            <div>

                                <i class="fa-regular fa-bookmark"></i>
                                <i class="fa-regular fa-heart"></i>
                            </div>
                        </div>
                    </div>
                    <div class="boxFooter">
                        <img src="https://cdn.dribbble.com/users/3113663/avatars/small/dcbf1db5e3d7b105ddad162aec88279d.jpg?1671115528"
                            alt="">
                        <p>Flowers bloom gracefully.</p>
                        <span id="pro">PRO</span>
                        <i class="fa-solid fa-heart">120</i><i class="fa-solid fa-eye">155k</i>
                    </div>
                </div>
                <div class="box">
                    <div class="boxImg">
                        <img src="https://cdn.dribbble.com/userupload/12470939/file/original-24b5051a1d994714ef3d2a87f6862940.jpg?resize=450x338&vertical=center"
                            alt="">
                        <div class="hover">
                            <h6>Music soothes souls.</h6>
                            <div>

                                <i class="fa-regular fa-bookmark"></i>
                                <i class="fa-regular fa-heart"></i>
                            </div>
                        </div>
                    </div>
                    <div class="boxFooter">
                        <img src="https://cdn.dribbble.com/users/3113663/avatars/small/dcbf1db5e3d7b105ddad162aec88279d.jpg?1671115528"
                            alt="">
                        <p>Music soothes souls.</p>
                        <span id="pro">PRO</span>
                        <i class="fa-solid fa-heart">120</i><i class="fa-solid fa-eye">155k</i>
                    </div>
                </div>
                <div class="box">
                    <div class="boxImg">
                        <img src="https://cdn.dribbble.com/userupload/12569469/file/original-de0700a6c188b05cc72e849aa26a26d5.jpg?resize=450x338&vertical=center"
                            alt="">
                        <div class="hover">
                            <h6>Fire crackles warmly.
                            </h6>
                            <div>

                                <i class="fa-regular fa-bookmark"></i>
                                <i class="fa-regular fa-heart"></i>
                            </div>
                        </div>
                    </div>
                    <div class="boxFooter">
                        <img src="https://cdn.dribbble.com/users/3113663/avatars/small/dcbf1db5e3d7b105ddad162aec88279d.jpg?1671115528"
                            alt="">
                        <p>Fire crackles warmly.
                        </p>
                        <span id="pro">PRO</span>
                        <i class="fa-solid fa-heart">120</i><i class="fa-solid fa-eye">155k</i>
                    </div>
                </div>
                <div class="box">
                    <div class="boxImg">
                        <img src="https://cdn.dribbble.com/userupload/12595034/file/original-4c33378bf89f8ed9b625d9115f373626.png?resize=450x338&vertical=center"
                            alt="">
                        <div class="hover">
                            <h6>Adventure awaits </h6>
                            <div>

                                <i class="fa-regular fa-bookmark"></i>
                                <i class="fa-regular fa-heart"></i>
                            </div>
                        </div>
                    </div>
                    <div class="boxFooter">
                        <img src="https://cdn.dribbble.com/users/3113663/avatars/small/dcbf1db5e3d7b105ddad162aec88279d.jpg?1671115528"
                            alt="">
                        <p>Adventure awaits .</p>
                        <span id="pro">PRO</span>
                        <i class="fa-solid fa-heart">120</i><i class="fa-solid fa-eye">155k</i>
                    </div>
                </div>
                <div class="box">
                    <div class="boxImg">
                        <img src="https://cdn.dribbble.com/userupload/12654807/file/original-32f355411cb9558f0ac77ab0547255d8.jpg?resize=450x338&vertical=center"
                            alt="">
                        <div class="hover">
                            <h6>Shadows dance playfully.</h6>
                            <div>

                                <i class="fa-regular fa-bookmark"></i>
                                <i class="fa-regular fa-heart"></i>
                            </div>
                        </div>
                    </div>
                    <div class="boxFooter">
                        <img src="https://cdn.dribbble.com/users/3113663/avatars/small/dcbf1db5e3d7b105ddad162aec88279d.jpg?1671115528"
                            alt="">
                        <p>Shadows dance .</p>
                        <span id="pro">PRO</span>
                        <i class="fa-solid fa-heart">120</i><i class="fa-solid fa-eye">155k</i>
                    </div>
                </div>
            </div>
            <button id="explore">Browse more inspiration</button>
        </section>
        <section class="join">
            <h2>Find your next <br> designer today</h2>
            <p>The world's leading brands use Dribbble th hire creative talent. <br>
            Browse millions of top-rated potfolios to find your perfect <br>creative match</p>
            <div class="btns">
                <button>Get started now</button>
                <button>Learn about hiring</button>
            </div>
            <h6>Are you a designer? <span>Join Dribbble</span></h6>
        </section>
        <div class="footerScroller">
            <div class="wrapper">
                <div class="wrapperContainer">
                    <img src="https://cdn.dribbble.com/userupload/12679462/file/original-7193f9870c124e32be881a2188e1b4da.jpg?format=webp&resize=320x240&vertical=center" alt="">
                </div>
                <div class="wrapperContainer">
                    <img src="https://cdn.dribbble.com/userupload/12498480/file/still-013124e346372b4636d3c889ca9523eb.png?format=webp&resize=320x240&vertical=center" alt="">
                </div>
                <div class="wrapperContainer">
                    <img src="https://cdn.dribbble.com/userupload/12507583/file/original-835018742d763134cb05b6d0ed8ed805.jpg?format=webp&resize=320x240&vertical=center" alt="">
                </div>
                <div class="wrapperContainer">
                    <img src="https://cdn.dribbble.com/userupload/12534458/file/original-fa614bf79c04dc02a66146a76b0f4fcc.jpg?format=webp&resize=320x240&vertical=center" alt="">
                </div>
            </div>
            <div class="wrapper">
                <div class="wrapperContainer">
                    <img src="https://cdn.dribbble.com/userupload/12679462/file/original-7193f9870c124e32be881a2188e1b4da.jpg?format=webp&resize=320x240&vertical=center" alt="">
                </div>
                <div class="wrapperContainer">
                    <img src="https://cdn.dribbble.com/userupload/12498480/file/still-013124e346372b4636d3c889ca9523eb.png?format=webp&resize=320x240&vertical=center" alt="">
                </div>
                <div class="wrapperContainer">
                    <img src="https://cdn.dribbble.com/userupload/12507583/file/original-835018742d763134cb05b6d0ed8ed805.jpg?format=webp&resize=320x240&vertical=center" alt="">
                </div>
                <div class="wrapperContainer">
                    <img src="https://cdn.dribbble.com/userupload/12534458/file/original-fa614bf79c04dc02a66146a76b0f4fcc.jpg?format=webp&resize=320x240&vertical=center" alt="">
                </div>
            </div>
        </div>
        <footer>
            <div class="footer-part1">
                <img src="./images/Dribbble-Logo.png" alt="">
                <div>
                    <a href="#">For designers</a>
                    <a href="#">Hire talents</a>
                    <a href="#">Inspiration</a>
                    <a href="#">Advertising</a>
                    <a href="#">Blog</a>
                    <a href="#">About</a>
                    <a href="#">Careers</a>
                    <a href="#">Support</a>
                </div>
                <div class="icons">
                    <i class="fa-brands fa-instagram"></i>
                    <i class="fa-brands fa-facebook"></i>
                    <i class="fa-brands fa-linkedin"></i>
                    <i class="fa-brands fa-twitter"></i>
                </div>
            </div>
            <div class="footer-part2">
                <div>
                    <span> &copy; 2024 Dribble</span>
                    <span>Terms</span>
                    <span>Privacy</span>
                    <span>Cookies</span>
                </div>
                <div>
                    <span>Jobs</span><span>designers</span><span>Freelancers</span><span>Tags</span><span>Places</span><span>Resources</span>
                </div>
            </div>
        </footer>
    </main>
</body>

</html>
```
## CSS code:
```
/* CSS Reset */
@font-face {
    font-family: heading;
    src: url(./vEFF2_tTDB4M7-auWDN0ahZJW3IX2ih5nk3AucvUHf6kDXr4.ttf);
  }
  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
  
  /* Global Styles */
  body,html {
    font-family: 'Arial', sans-serif;
    height : 100%;
    width: 100%;
    background-color: #F8F7F4;
  }
  main::selection{
    color: red;
  }
  
  /* Add your own styles below this line */
  main{
    width: 100%;
  
  }
  /* .....HeroContainer .....  */
  .heroContainer{
    width: 100%;
    height: 100vh;
  }
  /* ......navbar ......  */
  .heroContainer nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    height: 16.8vh;
    padding: 0 3.4vw;
  }
  .heroContainer nav .links a{
    color: black;
    text-decoration: none;
    font-weight: 600;
    font-size: 1.1vw;
  }
  .links{
    /* width: 35%; */
    display: flex;
    gap: 2.5vw; 
    align-items: center;
    justify-content: center;
  
  }
  .signUps{
    display: flex;
    align-items: center;
    gap: 2vw;
  }
  .links img{
    /* width: 7vw; */
    height: 4vw;
    margin-top: -10px;
  }
  #Login{
    border: none;
    outline: none;
    font-weight: 600;
  }
  #signIn{
    background-color: #0D0C22;
    color: white;
    font-size: 1.1vw;
    font-weight: 600;
    padding: 1.3vw 2vw;
    outline: none;
    border: none;
    border-radius: 2vw;
  }
  .signUps input{
    padding: 1.3vw 2vw;
    border-radius: 2vw;
    border: none;
    background-color: #FFFFFF;
  }
  .links i{
    display: none;
  }
  
  /* .......Hero section .....  */
  .hero{
    width: 100%;
    height: calc(100% - 16.8vh);
    /* background-color: cadetblue; */
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    gap: 3vw;
    padding: 3vw 0 0 0;
  }
  .hero h2{
    background-color: #FFDA7A;
    padding: 0.7vw 1.6vw;
    border-radius: 2vw;
    font-size: 1.3vw;
    font-family: heading;
    font-weight: 650;
  }
  .hero h1{
    font-size: 5.5vw;
    font-family: heading;
    font-weight: 500;
    line-height: 5.4vw;
  }
  .hero p{
    font-size: 1.6vw;
  }
  
  /* ......Scroller ...... */
  .scrollerContainer{
    display: flex;
    overflow-x:hidden ;
    gap: 26px;
    flex-wrap: nowrap;
  }
  .scroller{
    width: fit-content;
    flex-shrink: 0;
    height: 59vh;
    display: flex;
    gap: 30px;
    flex-wrap: nowrap;
    padding: 0.5vw;
    overflow: hidden;
    animation: anime;
    animation-duration: 60s;
    animation-timing-function: linear;
    animation-iteration-count: infinite;
  }
  .scroller .elem{
    flex-shrink: 0;
    width: 22vw;
    height: 100%;
    background-color: yellow;
    border-radius: 3vw;
    overflow: hidden;
    position: relative;
  }
  .overlay{
    height: 40%;
    width: 100%;
    position: absolute;
    bottom: 0;
    display: flex;
    flex-direction: column;
    padding: 1vw  1.2vw;
    color: white;
    font-weight: 500;
  }
  .overlay p{
    font-size: 1.5vw;
    font-weight: 500;
  }
  .overlay div{
    margin-top: 1.7vw;
  }
  .overlay span{
    padding: 0.5vw 1vw;
    border: 0.5px solid white;
    font-size: 1vw;
    border-radius: 3vw;
  }
  @keyframes anime {
    from{
      transform: translateX(0);
    }
    to{
      transform: translateX(calc(-100% - 30px));
    }
  }
  .scroller .elem img, .scroller .elem video{
    object-fit: cover;
    object-position: center;
    width: 100%;
    height: 100%; 
  }
  /* Explore Page  */
  section{
    width: 100%;
    /* min-height: 100vh;   */
    padding: 4vw 6vw;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  section h2{
    font-size: 4vw;
    font-weight: 200;
    text-align: center;
    margin-bottom: 4vw;
  }
  section .box{
    width: 26vw;
    height: 25vw;
    border-radius: 10px;
    overflow: hidden;
    display: inline-block;
    margin: 12px;
  
  }
  .hover{
    width: 100%;
    height: 40%;
    position: absolute;
    bottom: 0;
    background: linear-gradient(rgba(255, 254, 254, 0),rgb(2, 2, 2));
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 2vw 1.2vw 0.2vw 1.2vw;
    opacity: 0;
    transition: all linear 0.2s;
  }
  section .box .boxImg:hover .hover{
    opacity: 1;
  }
  .hover h6{
    font-size: 1.52vw;
    color: white;
    font-weight: 100;
  }
  .hover i{
    background-color: white ;
    padding: 10px 12px;
    border-radius: 50%;
  }
  section .box .boxImg{
    width: 100%;
    height: 85%;
    position: relative;
    overflow: hidden;
    border-radius: 10px;
  }
  section .box .boxImg img{
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: center;
  }
  section .box .boxFooter{
    width: 100%;
    height: 15%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    color: #4e4e4e;
  }
  section .box .boxFooter img{
    width: 1.8vw;
    border-radius: 50%;
  }
  .boxFooter i{
    font-size: 1.1vw;
  }
  section .box .boxFooter p{
    font-size: 1vw;
    color: black;
  }
  #pro{
    background-color: #828282;
    color: white;
    font-size: 1vw;
    padding: 0.5vw;
    border-radius: 12px;
  }
  #explore{
    font-size: 1.1vw;
    padding: 1.2vw 1.8vw;
    border-radius: 2vw;
    border: 2px solid black;
    background-color: transparent;
    margin-top: 2vw;
  }
  
  /* ......Joining Section ......  */
  .join{
    width: 100%;
    height: 100vh;
    background-color: #FFDA79;
    text-align: center;
    align-items: center;
    justify-content: center;
    gap: 3vw;
  }
  .join h2{ 
    font-family: heading;
    font-size: 5vw;
    margin: 0;
    line-height: 5.5vw;
  }
  .join p{
    font-size: 1.6vw;
    font-weight: 100;
    color: #393939;
    line-height: 3vw;
  
  }
  .join .btns{
    gap: 1.5vw;
    display: flex;
  }
  .join .btns button{
    width: 13vw;
    height: 4.5vw;
    background-color: #0D0C22;
    color: white;
    border: none;
    border-radius: 3vw;
    font-weight: 600;
    font-size: 1.2vw;
  }
  .join .btns button:last-child{
    background-color: white;
    color: black;
  }
  .join h6{
    font-size: 1.6vw;
    font-weight: 300;
    margin-top: 1.5vw;
    color: #393939;
  }
  .join h6 span{
    text-decoration: underline;
  }
  /* ......Footer ....  */
  .footerScroller{
    width: 100%;
    height: 40vh;
    padding: 1.5vw;
    display: flex;
    flex-wrap: nowrap;
    gap: 30px;
    overflow: hidden;
  }
  .wrapper{
    width:fit-content  ;
    height: 100%;
    display: flex;
    gap: 30px;
    flex-shrink: 0;
    animation-name: marquee;
    animation-duration: 10s;
    animation-iteration-count: infinite;
    animation-timing-function: linear;
  }
  @keyframes marquee {
    from{
      transform: translateX(0);
    }
    to{
      transform: translateX(calc(-100% - 34px));
    }
  }
  .wrapperContainer{
    width: 20vw;
    height: 100%;
  border-radius: 20px;
  overflow: hidden;
  
  }
  .wrapperContainer img{
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: center;
  }
  footer{
    width: 100%;
    height: 35vh;
    margin-top: 2vw;
    padding: 2vw 3vw;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }
  .footer-part1{
    display: flex;
    align-items: center;
    justify-content: space-between;
  
  }
  .footer-part1 img{
    height: 5vw;
    margin-top: -10px;
  }
  .footer-part1 .icons i{
    font-size: 1.2vw;
    
  }
  .footer-part1 div{
    display: flex;
    gap: 2.4vw;
    font-weight: 600;
    flex-wrap: wrap;
    justify-content: center;
  }
  .footer-part1 div a{
    color: black;
    text-decoration: none;
    font-size: 1.2vw;
  }
  .footer-part2{
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .footer-part2 div{
    display: flex;
    gap: 1.2vw;
    color: #828282;
  }
```
