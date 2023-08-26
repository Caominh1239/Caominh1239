game:GetService("UserInputService").JumpRequest:Connect(function()
		if infjumpenabled == true then
			game.Players.LocalPlayer.Character:FindFirstChild("Humanoid"):ChangeState("Jumping")
		end
	end)
end
