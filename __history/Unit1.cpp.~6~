//---------------------------------------------------------------------------

#include <fmx.h>
#pragma hdrstop

#include "Unit1.h"
//---------------------------------------------------------------------------
#pragma package(smart_init)
#pragma resource "*.fmx"
TForm1 *Form1;
//---------------------------------------------------------------------------
__fastcall TForm1::TForm1(TComponent* Owner)
	: TForm(Owner)
{
}
//---------------------------------------------------------------------------
void __fastcall TForm1::addTaskClick(TObject *Sender)
{
	if (taskInputField->Text != "") {
		TasksListBox->Items->Add(taskInputField->Text);
		taskInputField->Text = "";
	}

}
//---------------------------------------------------------------------------
void __fastcall TForm1::TasksListBoxItemClick(TCustomListBox * const Sender, TListBoxItem * const Item)

{
	TasksListBox->Items->Delete(Item->Index);
}
//---------------------------------------------------------------------------
