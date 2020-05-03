# FizzBuzz_JavaScript \n

describe('A FizzBuzz program', () => {
    it('has a smoke test', () => {
        expect(true) toBe(true)
        expect(true).not.toBE(false)
    })
    describe('A fizz() function', () => {
        it('throws an error if there is no input', () => {
            expect(fizz()).toThrow()
        })
    })
})
