public class BubbleSort {

	
	public static void main(String[] args) {
		BubbleSort bs = new BubbleSort();
		int[] arr = bs.random();
		long startTime = System.nanoTime();
		bs.bubbleSort(arr);
		long endTime = System.nanoTime();
		long totalTime = endTime - startTime;
		double secs = totalTime/ 1000000000.00;
		bs.printArray(arr);
		System.out.println(secs + "sec");
	}

	int[] random() {
		int[] arr = new int[10000000];
		for(int i=0; i<arr.length; i++) {
			double num = Math.random() * 10000.0;
			arr[i] = (int) num;
		}
		return arr;
	}
	
	void printArray(int[] array) {
		
		for(int i=0; i<array.length; i++) {
			System.out.println(array[i]);
		}
	}
	
	void bubbleSort(int arr[]) 
    { 
        int n = arr.length; 
        for (int i = 0; i < n-1; i++) 
            for (int j = 0; j < n-i-1; j++) 
                if (arr[j] > arr[j+1]) 
                { 
                    int temp = arr[j]; 
                    arr[j] = arr[j+1]; 
                    arr[j+1] = temp; 
                } 
    } 
}
