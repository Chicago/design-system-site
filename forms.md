---

layout: city-page

---

<div class="container">
    <div class="row">
        <div class="col-lg-6 col-md-12 col-sm-12">
            <h2>Sign Up form</h2>
            <form name="sign-up">
                    <div class="form-group">
                        <label for="inputSalutation">Salutation</label>
                        <select class="custom-select" id="inputSalutation">
                            <option selected="">Select</option>
                            <option value="1">Mr.</option>
                            <option value="2">Sr.</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label for="inputFirstName">First name *</label>
                        <input type="text" class="form-control is-invalid" id="inputFirstName"  placeholder="Enter first name">
                        <div class="invalid-feedback" style="display: block;">Please provide a valid value.</div>
                    </div>
                    <div class="form-group">
                        <label for="inputMidName">Middle name <small>- optional</small></label>
                        <input type="text" class="form-control" id="inputMidName"  placeholder="Enter middle name">
                    </div>
                    <div class="form-group">
                        <label for="inputLastName">Last name </label>
                        <input type="text" class="form-control" id="inputLastName"  placeholder="Enter last name">
                    </div>
                    <div class="form-group">
                        <label for="inputEmail">Email address *</label>
                        <input type="email" class="form-control" id="inputEmail" aria-describedby="emailHelp" placeholder="Enter email">
                        <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
                    </div>
                    <div class="form-group">
                        <label for="inputEmailc">Confirm email address *</label>
                        <input type="email" class="form-control" id="inputEmailc" aria-describedby="emailHelpc" placeholder="Confirm email">
                        <small id="emailHelpc" class="form-text text-muted">Confirm your email address.</small>
                    </div>
                    <div class="form-group">
                        <label for="inputPassword">Password *</label>
                        <input type="password" class="form-control" id="inputPassword" aria-describedby="passHelp" placeholder="Enter password">
                        <small id="passHelp" class="form-text text-muted">Password must be between 6 to 16 characters.</small>
                    </div>
                    <div class="form-group">
                        <label for="inputPasswordc">Confirm password *</label>
                        <input type="password" class="form-control" id="inputPasswordc" aria-describedby="passHelpc" placeholder="Confirm password">
                        <small id="passHelpc" class="form-text text-muted">Confirm your Password.</small>
                    </div>
                    <div class="form-group">
                        <button class="btn btn-outline-primary">Cancel</button>
                        <button class="btn btn-primary">Save</button>
                    </div>
               
            </form>
        </div>
        <div class="col-lg-6 col-md-12 col-sm-12">
            <h2>Sign In form</h2>
            <form name="sign-in">
                <div class="form-group">
                    <label for="inputEmail">Username or email address *</label>
                    <input type="email" class="form-control" id="inputEmail" aria-describedby="emailHelp" placeholder="Enter email">
                </div>
                <div class="form-group">
                    <label for="inputPasswordsi">Password *</label>
                    <input type="password" class="form-control" id="inputPasswordsi" placeholder="Enter password">
                    <a href="#" class="btn btn-link btn-sm float-right">Show Password</a>
                </div>
                <div class="form-group">
                    <button class="btn btn-primary btn-lg">Sign in</button>
                </div>
                <div class="form-group">
                    <a href="#" class="btn btn-link">Forgot username?</a><br>
                    <a href="#" class="btn btn-link">Forgot password?</a>
                </div>
            </form>
            <hr>
            <h2 class="mt-5">Reset Password</h2>
            <form name="reset-password">
                <div class="mb-2 alert alert-primary" role="alert">
                    <div class="alert-icon-lg"><i class="fas fa-info-circle"></i></div>
                    <div class="alert-content">
                        <h4 class="alert-heading">Password Information</h4>
                        <p>Instructions and usefull information to provide to users.</p>
                    </div>
                  </div>
                <div class="form-group">
                    <label for="inputPasswordFp">Password *</label>
                    <input type="password" class="form-control" id="inputPasswordFp" placeholder="Enter password">
                </div>
                <div class="form-group">
                    <label for="inputPasswordFpc">Confirm password *</label>
                    <input type="password" class="form-control" id="inputPasswordFpc" placeholder="Confirm password">
                    <a href="#" class="btn btn-link btn-sm float-right">Show Password</a>
                </div>
                <div class="form-group">
                    <button class="btn btn-primary">Reset password</button>
                </div>
            </form>
        </div>
    </div>
    <hr>
    <div class="row">
        <div class="col-lg-6 col-md-12 col-sm-12">
            <h2>Address</h2>
            <form name="address">
                <div class="form-group">
                    <label for="inputAddress1">Address line 1 *</label>
                    <input type="text" class="form-control" id="inputAddress1"  placeholder="Enter address line 1">
                </div>
                <div class="form-group">
                    <label for="inputAddress2">Address line 2 <small>- optional</small></label>
                    <input type="text" class="form-control" id="inputAddress2"  placeholder="Enter address line 1">
                </div>
                <div class="form-row">
                    <div class="col">
                        <div class="form-group">
                            <label for="inputCity1">City *</label>
                            <input type="text" class="form-control" id="inputCity1"  placeholder="Enter city name">
                        </div>
                    </div>
                    <div class="col">
                        <div class="form-group">
                            <label for="inputState">State *</label>
                            <select class="custom-select" id="inputState">
                                <option selected="">Select</option>
                                <option value="1">Illinois</option>
                                <option value="2">Nebraska</option>
                            </select>
                        </div>
                    </div>
                </div>
                <div class="form-row">
                    <div class="col-6">
                        <div class="form-group">
                            <label for="inputZip">ZIP Code *</label>
                            <input type="text" class="form-control" id="inputZip"  placeholder="Enter ZIP code">
                        </div>
                    </div>
                </div>
                
                
                <div class="form-group text-right">
                    <button class="btn btn-outline-primary">Cancel</button>
                    <button class="btn btn-primary">Save</button>
                </div>
            </form>
        </div>
        <div class="col-lg-6 col-md-12 col-sm-12">
            <h2>Payment</h2>
            <form name="payment">
                <div class="form-group">
                    <label for="inputCardnumber">Card number *</label>
                    <input type="text" class="form-control" id="inputCardnumber"  placeholder="Enter credit card number">
                </div>

                <div class="form-row">
                    <div class="col">
                        <div class="form-group">
                            <label for="inputCardexp">Expiration Date *</label>
                            <input type="text" class="form-control" id="inputCardexp"  placeholder="MM/ yyyy">
                        </div>
                    </div>
                    <div class="col">
                        <div class="form-group">
                            <label for="inputCardcode">Secure code *</label>
                            <input type="text" class="form-control" id="inputCardcode"  placeholder="Enter security code">
                        </div>
                    </div>
                </div>

                <div class="form-group">
                    <label for="inputCardname">Name on card *</label>
                    <input type="text" class="form-control" id="inputCardname"  placeholder="Enter name on credit card">
                </div>
                <div class="form-group text-right">
                    <button class="btn btn-outline-primary">Cancel</button>
                    <button class="btn btn-primary">Proceed</button>
                </div>
            </form>
        </div>
    </div>
</div>
