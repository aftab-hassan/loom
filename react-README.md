1. ref

2. promises
 public validateCreateListItem(
     listUrl: string,
     itemId: number,
     formValues: IListItemFormUpdateValue[],
     bNewDocumentUpdate: boolean,
     checkInComment: string | null,
     datesInUTC: boolean
   ): Promise<any> {
     return new Promise((resolve, reject) => {
       console.log('It is done.');
        Succeed half of the time.
       if (2 > 1) {
         resolve('SUCCESS');
       } else {
         reject('FAILURE');
       }
     });
   }

3. Thinking in react hooks - https://wattenberger.com/blog/react-hooks

4. 