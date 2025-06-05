impl Solution {
    pub fn plus_one(digits: Vec<i32>) -> Vec<i32> {
        let n = digits.len();
        let mut ans = Vec::new();
        let mut carry = 1;

        for i in (0..n).rev() {
            let sum = digits[i] + carry;
            ans.push(sum % 10);
            carry = sum / 10;
        }

        if carry == 1 {
            ans.push(1);
        }

        ans.reverse();
        ans
    }
}
