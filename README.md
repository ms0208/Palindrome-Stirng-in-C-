# Palindrome-Stirng-in-C-
#include <bits/stdc++.h>
using namespace std;

stirng isPlaindrome
{
    // string S
    string P = S;
 
    // Reverse the string P
    reverse(P.begin(), P.end());
 
    // If S is equal to P
    if (S == P)
    {
        // Return "Yes"
        return "Yes";
    }
    // Otherwise
    else
    {
        // return "No"
        return "No";
    }
}
 
// Driver Code
int main()
{
    string S = "ABCDCBA";
    cout << isPalindrome(S);
 
    return 0;
}
