<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HAMMAD LOGIN FORM </title>
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        .login-form-wrap {
            width: 100%;
            height: 100vh;
            background-image: url('https://res.cloudinary.com/dzeznhbhc/image/upload/v1686724235/samples/bgrond_21-ai_sl0fvv.png');
            background-repeat: no-repeat;
            background-position: center;
            background-position: center;
            background-size: cover;

            .login-box {
                display: flex;
                justify-content: center;
                align-items: center;
                flex-direction: column;
                height: 100%;

                .login-content-warp {
                    padding: 30px;
                    background: #505050d1;
                    width: 400px;
                    display: flex;
                    justify-content: center;
                    flex-direction: column;
                    align-items: center;
                    border-radius: 35px;
                    border-top: 5px solid #dac494;

                    .profile-form {
                        display: flex;
                        flex-direction: column;
                        align-items: center;

                        img {
                            width: 135px;
                            height: 135px;
                            object-fit: cover;
                            border-radius: 50%;
                        }

                        .profile-title {
                            font-size: 26px;
                            text-transform: capitalize;
                            font-weight: 600;
                            color: #dac494;
                            padding: 20px 0px;
                        }
                    }

                    .social-icon {
                        display: flex;
                        justify-content: center;
                        align-items: center;
                        display: flex;
                        column-gap: 16px;
                        padding: 10px 0px;

                        img {
                            width: 40px;
                            height: 40px;
                        }

                        span {
                            color: #dac494;
                            font-size: 16px;
                            font-weight: 500;
                        }

                        .social-icon-warp {
                            display: flex;
                            justify-content: center;
                            align-items: center;
                            column-gap: 10px;
                            text-decoration: none;
                        }
                    }

                    .butn-sign {
                        padding: 20px 0px;
                        width: 100%;
                        display: flex;
                        justify-content: center;
                        align-items: center;

                        button {
                            background-color: #e3d199;
                            color: #2a2a2a;
                            border: none;
                            font-weight: 600;
                            height: 40px;
                            width: 74%;
                            border-radius: 8px;
                            font-size: 16px;
                            text-transform: capitalize;
                            border: 2px solid #d8c491;

                            &:hover {
                                background-color: #9e9e9e00;
                                color: #fffcfc;
                                border: 2px solid #d8c491;
                                cursor: pointer;
                                transition: 1s;
                            }
                        }
                    }

                    form {
                        width: 100%;

                        .email-input,
                        .password-input {
                            margin: 12px 0px;
                            position: relative;

                            .email {
                                position: absolute;
                                top: 50%;
                                right: 0;
                                transform: translate(-50%, -50%);
                                font-size: 18px;
                                color: #7c7c7c;
                            }

                            input {
                                height: 47px;
                                border-radius: 8px;
                                border: none;
                                width: 100%;
                                font-size: 16px;
                                padding-left: 10px;

                                &:focus-visible {
                                    outline: none;
                                }

                                &::placeholder {
                                    color: gray;
                                }
                            }
                        }

                        .forget-link-warp {
                            display: flex;
                            justify-content: space-between;
                            align-items: center;
                            margin: 20px 0px;

                            .checkbox {
                                display: flex;
                                align-items: center;
                                column-gap: 10px;

                                input {
                                    width: 18px;
                                    height: 18px;
                                    border-radius: 4px;
                                }
                            }

                            span {
                                font-size: 16px;
                                color: #dcdcdc;
                                font-weight: 500;
                            }
                        }
                    }
                }
            }
        }


        @media screen and (max-width:576px) {
            .login-form-wrap {
                .login-box {
                    .login-content-warp {
                        width: 300px;

                        .profile-form {
                            img {
                                width: 80px;
                                height: 80px;
                            }

                            .profile-title {
                                font-size: 22px;
                            }
                        }

                        form {


                            .forget-link-warp {
                                span {
                                    font-size: 14px;
                                }
                            }
                        }

                    }
                }
            }
        }

        @media screen and (max-width:420px) {
            .login-form-wrap {

                .login-box {
                    .login-content-warp {
                        width: 270px;

                        form {
                            .forget-link-warp {
                                span {
                                    font-size: 13px;
                                }
                            }
                        }
                    }
                }
            }
        }
    </style>
</head>

<body>
    <div class="login-form-wrap">
        <div class="login-box">
            <div class="login-content-warp">
                <div class="profile-form">
                    <img src="https://i.ibb.co/2vwCds8/hammad.jpg"
                        alt="women">
                    <span class="profile-title">user login</span>
                </div>
                <form action="">
                    <div class="email-input">
                        <span class="email"><i class="fa-regular fa-envelope"></i> </span>
                        <input type="text" placeholder="email address">
                    </div>

                    <div class="password-input">
                        <span class="email"><i class="fa-solid fa-lock"></i></span>
                        <input type="password" placeholder="password">
                    </div>

                    <div class="forget-link-warp">
                        <div class="checkbox">
                            <input type="checkbox">
                            <span>keep me signed in</span>
                        </div>
                        <div>
                            <span>forget your password</span>
                        </div>
                    </div>
                </form>

                <div class="social-icon">
                    <a class="social-icon-warp" href="https://www.google.com/">
                        <img src="https://res.cloudinary.com/dzeznhbhc/image/upload/v1686725283/samples/google-plus_1_dbtrqm.png"
                            alt="">
                        <span>Login google</span>
                    </a>
                </div>

                <div class="butn-sign">
                    <button>sign in</button>
                </div>
            </div>
        </div>
    </div>
</body>

</html> 
