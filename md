package salenium;

public class Multiplication {
	public static int mul(int a, int b) {
        return a * b;
    }

}
tc
package salenium;

import static org.junit.jupiter.api.Assertions.*;

import org.junit.jupiter.api.Test;

class MultiplicationTest {
	 @Test
	    public void testMultiplication() {
	        int a = 5;
	        int b = 10;
	        int expected = 50;
	        int actual = a * b;
	        assertEquals(expected, actual);
	    }

}
div
package salenium;

public class Division {
	public static int div(int a, int b) {
        return a / b;
    }

}
tc
package salenium;

import static org.junit.jupiter.api.Assertions.*;

import org.junit.jupiter.api.Test;

class DivisionTest {

	@Test
	    public void testDivion() {
	        int a = 10;
	        int b = 5;
	        int expected = 2;
	        int actual = a / b;
	        assertEquals(expected, actual);
	    
	}

}
