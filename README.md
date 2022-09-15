# README

create a myrecipes app

Minitest

-Integration testing
-Model Testing-unit testing

rails generate intergration_test pages(command to generate test)

we would write up testcases in the test/pages 
such as :
 test "Should get home" do
    get pages_home_url
    assert_response :success
end


