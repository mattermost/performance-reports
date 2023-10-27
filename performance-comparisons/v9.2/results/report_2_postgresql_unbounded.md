### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| CommandWebhookStore.Cleanup | avg | 6ms | 26ms | 20ms | 322.05
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 3ms | 10ms | 7ms | 263.88
| StatusStore.UpdateExpiredDNDStatuses | avg | 5ms | 16ms | 11ms | 211.00
| PluginStore.List | avg | 4ms | 11ms | 7ms | 158.99
| SessionStore.GetSessionsExpired | avg | 4ms | 9ms | 5ms | 120.50
| ChannelStore.AutocompleteInTeamForSearch | avg | 86ms | 181ms | 95ms | 110.30
| TokenStore.Cleanup | avg | 8ms | 17ms | 9ms | 107.54
| JobStore.UpdateOptimistically | avg | 5ms | 10ms | 5ms | 104.86
| JobStore.UpdateStatusOptimistically | avg | 5ms | 10ms | 5ms | 96.18
| TeamStore.AnalyticsTeamCount | avg | 4ms | 8ms | 4ms | 95.50
| JobStore.Get | avg | 7ms | 13ms | 6ms | 84.45
| PostPersistentNotificationStore.Get | avg | 4ms | 6ms | 2ms | 56.51
| SessionStore.Remove | avg | 4ms | 6ms | 2ms | 50.94
| PluginStore.Get | avg | 6ms | 9ms | 3ms | 47.20
| JobStore.UpdateStatus | avg | 5ms | 7ms | 2ms | 39.66
| JobStore.GetCountByStatusAndType | avg | 11ms | 15ms | 4ms | 37.94
| RoleStore.ChannelHigherScopedPermissions | avg | 8ms | 11ms | 3ms | 37.39
| UserStore.GetByUsername | avg | 9ms | 12ms | 3ms | 32.02
| PostStore.SearchPostsForUser | avg | 188ms | 235ms | 47ms | 25.05
| UserStore.Count | avg | 24ms | 30ms | 6ms | 24.92
| ThreadStore.Get | avg | 8ms | 10ms | 2ms | 24.76
| PostStore.SetPostReminder | avg | 22ms | 27ms | 5ms | 22.24
| BotStore.Get | avg | 9ms | 11ms | 2ms | 21.42
| JobStore.GetNewestJobByStatusesAndType | avg | 10ms | 12ms | 2ms | 19.25
| SessionStore.Get | avg | 11ms | 13ms | 2ms | 18.11
| ReactionStore.Save | avg | 22ms | 24ms | 2ms | 9.15
| ChannelStore.UpdateSidebarCategories | avg | 128ms | 134ms | 6ms | 4.67
| ChannelStore.SaveMember | avg | 53ms | 55ms | 2ms | 3.77
| UserStore.GetAllProfilesInChannel | avg | 407ms | 418ms | 11ms | 2.70
| UserStore.AutocompleteUsersInChannel | avg | 76ms | 78ms | 2ms | 2.62
| StatusStore.SaveOrUpdate | avg | 94ms | 96ms | 2ms | 2.12
| ChannelStore.GetMembers | avg | 204ms | 207ms | 3ms | 1.47
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 5ms | 49ms | 44ms | 888.89
| TeamStore.AnalyticsTeamCount | p99 | 5ms | 48ms | 43ms | 868.20
| JobStore.UpdateStatusOptimistically | p99 | 37ms | 163ms | 126ms | 338.16
| SessionStore.GetSessionsExpired | p99 | 24ms | 96ms | 72ms | 300.62
| UserStore.Count | p99 | 49ms | 167ms | 118ms | 238.90
| JobStore.UpdateOptimistically | p99 | 37ms | 89ms | 52ms | 139.64
| ThreadStore.Get | p99 | 80ms | 177ms | 97ms | 120.88
| PluginStore.List | p99 | 39ms | 86ms | 47ms | 119.75
| SessionStore.Remove | p99 | 22ms | 46ms | 24ms | 109.09
| StatusStore.UpdateExpiredDNDStatuses | p99 | 45ms | 94ms | 49ms | 108.89
| TokenStore.Cleanup | p99 | 25ms | 50ms | 25ms | 101.21
| CommandWebhookStore.Cleanup | p99 | 25ms | 50ms | 25ms | 101.21
| PluginStore.Get | p99 | 24ms | 48ms | 24ms | 98.36
| ChannelStore.UpdateSidebarCategories | p99 | 473ms | 863ms | 390ms | 82.39
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.576s | 4.587s | 2.011s | 78.07
| UserStore.GetByUsername | p99 | 86ms | 137ms | 51ms | 59.02
| ChannelStore.GetMembersForUserWithPagination | p99 | 50ms | 76ms | 26ms | 52.39
| ChannelStore.Save | p99 | 238ms | 343ms | 105ms | 44.10
| RoleStore.ChannelHigherScopedPermissions | p99 | 46ms | 62ms | 16ms | 35.07
| PostStore.GetPostsAfter | p99 | 69ms | 87ms | 18ms | 26.11
| JobStore.Get | p99 | 74ms | 92ms | 18ms | 24.17
| StatusStore.Get | p99 | 51ms | 62ms | 11ms | 21.38
| PostStore.GetPosts | p99 | 67ms | 80ms | 13ms | 19.37
| GroupStore.GetByName | p99 | 60ms | 70ms | 10ms | 16.68
| UserTermsOfServiceStore.GetByUser | p99 | 60ms | 70ms | 10ms | 16.66
| LinkMetadataStore.Save | p99 | 78ms | 90ms | 12ms | 15.29
| SessionStore.Get | p99 | 137ms | 157ms | 20ms | 14.63
| FileInfoStore.AttachToPost | p99 | 97ms | 111ms | 14ms | 14.41
| PostPersistentNotificationStore.Get | p99 | 42ms | 48ms | 6ms | 14.20
| ChannelStore.SaveMember | p99 | 348ms | 395ms | 47ms | 13.49
| UserStore.IsEmpty | p99 | 30ms | 34ms | 4ms | 13.49
| UserStore.Update | p99 | 183ms | 205ms | 22ms | 12.01
| TeamStore.GetByName | p99 | 70ms | 78ms | 8ms | 11.45
| SystemStore.GetByName | p99 | 54ms | 60ms | 6ms | 11.16
| FileInfoStore.SetContent | p99 | 173ms | 192ms | 19ms | 10.97
| PostPersistentNotificationStore.GetSingle | p99 | 57ms | 63ms | 6ms | 10.50
| PreferenceStore.GetAll | p99 | 76ms | 83ms | 7ms | 9.26
| GroupStore.GetGroups | p99 | 65ms | 71ms | 6ms | 9.21
| FileInfoStore.GetForPost | p99 | 77ms | 84ms | 7ms | 9.09
| ChannelStore.GetFileCount | p99 | 78ms | 85ms | 7ms | 8.94
| TeamStore.GetTeamsByUserId | p99 | 69ms | 75ms | 6ms | 8.67
| PostStore.GetPostIdAfterTime | p99 | 49ms | 53ms | 4ms | 8.15
| PostStore.GetPostReminderMetadata | p99 | 42ms | 45ms | 3ms | 7.10
| TeamStore.GetTeamsForUser | p99 | 73ms | 78ms | 5ms | 6.82
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 46ms | 49ms | 3ms | 6.49
| PostStore.GetPostsByThread | p99 | 80ms | 85ms | 5ms | 6.28
| AuditStore.Save | p99 | 64ms | 68ms | 4ms | 6.25
| UserStore.GetForLogin | p99 | 66ms | 70ms | 4ms | 6.09
| UserStore.UpdateFailedPasswordAttempts | p99 | 67ms | 71ms | 4ms | 5.94
| PostStore.SetPostReminder | p99 | 228ms | 239ms | 11ms | 4.84
| JobStore.UpdateStatus | p99 | 44ms | 46ms | 2ms | 4.58
| SessionStore.UpdateLastActivityAt | p99 | 67ms | 70ms | 3ms | 4.50
| JobStore.GetAllByStatus | p99 | 90ms | 94ms | 4ms | 4.45
| ChannelStore.IncrementMentionCount | p99 | 69ms | 72ms | 3ms | 4.33
| UserStore.UpdateUpdateAt | p99 | 47ms | 49ms | 2ms | 4.22
| TeamStore.GetAllPage | p99 | 72ms | 75ms | 3ms | 4.17
| ReactionStore.Save | p99 | 220ms | 229ms | 9ms | 4.09
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 74ms | 77ms | 3ms | 4.06
| ThreadStore.GetTotalUnreadMentions | p99 | 75ms | 78ms | 3ms | 3.99
| ChannelStore.GetMemberCount | p99 | 178ms | 185ms | 7ms | 3.92
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 77ms | 80ms | 3ms | 3.92
| StatusStore.SaveOrUpdate | p99 | 945ms | 982ms | 37ms | 3.92
| PostStore.Save | p99 | 222ms | 229ms | 7ms | 3.16
| UserStore.GetAllProfilesInChannel | p99 | 1.997s | 2.059s | 62ms | 3.10
| ChannelStore.GetPublicChannelsForTeam | p99 | 97ms | 100ms | 3ms | 3.08
| ThreadStore.MaintainMembership | p99 | 167ms | 172ms | 5ms | 2.99
| ThreadStore.GetMembershipForUser | p99 | 76ms | 78ms | 2ms | 2.64
| ThreadStore.GetTotalThreads | p99 | 76ms | 78ms | 2ms | 2.63
| ThreadStore.MarkAllAsReadByChannels | p99 | 81ms | 83ms | 2ms | 2.47
| ChannelStore.GetGuestCount | p99 | 82ms | 84ms | 2ms | 2.44
| ChannelStore.GetMembersForUser | p99 | 87ms | 89ms | 2ms | 2.30
| ChannelStore.GetChannels | p99 | 88ms | 90ms | 2ms | 2.27
| SessionStore.Save | p99 | 94ms | 96ms | 2ms | 2.13
| PostStore.GetPostsSince | p99 | 182ms | 185ms | 3ms | 1.65
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 242ms | 245ms | 3ms | 1.24
| PostStore.SearchPostsForUser | p99 | 2.348s | 2.372s | 24ms | 1.02
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.CreateSidebarCategory | avg | 79ms | 33ms | -46ms | -58.58
| PreferenceStore.DeleteCategoryAndName | avg | 19ms | 8ms | -11ms | -58.45
| PostStore.Delete | avg | 74ms | 31ms | -43ms | -58.27
| UserStore.GetMany | avg | 9ms | 5ms | -4ms | -46.14
| JobStore.Save | avg | 15ms | 8ms | -7ms | -46.09
| ChannelStore.SearchGroupChannels | avg | 22ms | 12ms | -10ms | -44.75
| UserAccessTokenStore.GetByToken | avg | 10ms | 6ms | -4ms | -41.26
| PostAcknowledgementStore.GetForPost | avg | 11ms | 7ms | -4ms | -37.55
| ChannelStore.CreateInitialSidebarCategories | avg | 53ms | 33ms | -20ms | -37.50
| ChannelStore.GetSidebarCategory | avg | 31ms | 21ms | -10ms | -31.80
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 47ms | 32ms | -15ms | -31.73
| PostStore.GetPostReminders | avg | 20ms | 14ms | -6ms | -29.37
| ChannelStore.GetMembersForUserWithPagination | avg | 27ms | 21ms | -6ms | -22.49
| ClusterDiscoveryStore.SetLastPingAt | avg | 10ms | 8ms | -2ms | -20.28
| PostStore.AnalyticsPostCount | avg | 526ms | 446ms | -80ms | -15.21
| ChannelStore.GetTeamChannels | avg | 34ms | 29ms | -5ms | -14.72
| ChannelStore.Save | avg | 37ms | 34ms | -3ms | -8.15
| ProductNoticesStore.ClearOldNotices | avg | 38ms | 36ms | -2ms | -5.32
| ChannelStore.CreateDirectChannel | avg | 62ms | 59ms | -3ms | -4.81
| UserStore.GetProfilesInChannel | avg | 266ms | 254ms | -12ms | -4.52
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelStore.CreateSidebarCategory | p99 | 246ms | 50ms | -196ms | -79.84
| JobStore.Save | p99 | 368ms | 85ms | -283ms | -77.01
| PostStore.GetPostReminders | p99 | 220ms | 89ms | -131ms | -59.55
| PostAcknowledgementStore.GetForPost | p99 | 98ms | 45ms | -53ms | -54.08
| UserStore.GetMany | p99 | 86ms | 41ms | -45ms | -52.32
| ChannelStore.GetSidebarCategory | p99 | 218ms | 106ms | -112ms | -51.38
| UserAccessTokenStore.GetByToken | p99 | 90ms | 45ms | -45ms | -50.00
| PostPersistentNotificationStore.DeleteExpired | p99 | 42ms | 22ms | -20ms | -47.34
| BotStore.Get | p99 | 90ms | 48ms | -42ms | -46.67
| JobStore.GetCountByStatusAndType | p99 | 169ms | 102ms | -67ms | -39.64
| TeamStore.GetMember | p99 | 40ms | 27ms | -13ms | -32.49
| PostStore.Update | p99 | 205ms | 149ms | -56ms | -27.32
| UserStore.GetProfilesInChannel | p99 | 895ms | 692ms | -203ms | -22.68
| JobStore.GetNewestJobByStatusesAndType | p99 | 169ms | 131ms | -38ms | -22.49
| ChannelStore.CreateDirectChannel | p99 | 493ms | 387ms | -106ms | -21.49
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 68ms | 55ms | -13ms | -19.25
| ChannelStore.SearchGroupChannels | p99 | 99ms | 88ms | -11ms | -11.11
| PostStore.Delete | p99 | 245ms | 229ms | -16ms | -6.54
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 68ms | 64ms | -4ms | -5.90
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 233ms | 220ms | -13ms | -5.59
| PluginStore.Delete | p99 | 44ms | 42ms | -2ms | -4.60
| ClusterDiscoveryStore.SetLastPingAt | p99 | 93ms | 89ms | -4ms | -4.30
| StatusStore.UpdateLastActivityAt | p99 | 72ms | 69ms | -3ms | -4.19
| ChannelStore.GetTeamChannels | p99 | 97ms | 93ms | -4ms | -4.12
| ChannelStore.GetMember | p99 | 49ms | 47ms | -2ms | -4.11
| PostStore.GetSingle | p99 | 73ms | 70ms | -3ms | -4.10
| PostPriorityStore.GetForPost | p99 | 49ms | 47ms | -2ms | -4.06
| PreferenceStore.DeleteCategoryAndName | p99 | 49ms | 47ms | -2ms | -4.06
| TeamStore.Get | p99 | 68ms | 66ms | -2ms | -2.93
| LinkMetadataStore.Get | p99 | 77ms | 75ms | -2ms | -2.59
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| root | avg | 0s | 14ms | 14ms | 9862.07
| getGroupsAssociatedToChannelsByTeam | avg | 3ms | 11ms | 8ms | 295.54
| getChannelMembers | avg | 11ms | 30ms | 19ms | 172.17
| autocompleteChannelsForTeamForSearch | avg | 86ms | 181ms | 95ms | 110.21
| getUsers | avg | 12ms | 25ms | 13ms | 108.97
| getGroups | avg | 3ms | 5ms | 2ms | 58.37
| logout | avg | 101ms | 149ms | 48ms | 47.50
| getPostsForChannelAroundLastUnread | avg | 46ms | 64ms | 18ms | 39.43
| searchPostsInTeam | avg | 210ms | 267ms | 57ms | 27.18
| removeUserCustomStatus | avg | 227ms | 288ms | 61ms | 26.90
| getRolesByNames | avg | 8ms | 10ms | 2ms | 25.36
| updateUserCustomStatus | avg | 287ms | 332ms | 45ms | 15.70
| login | avg | 133ms | 148ms | 15ms | 11.27
| createGroupChannel | avg | 638ms | 708ms | 70ms | 10.97
| saveReaction | avg | 55ms | 58ms | 3ms | 5.48
| setPostReminder | avg | 70ms | 72ms | 2ms | 2.86
| uploadFileStream | avg | 515ms | 524ms | 9ms | 1.75
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| root | p99 | 5ms | 235ms | 230ms | 4646.46
| getGroupsAssociatedToChannelsByTeam | p99 | 5ms | 49ms | 44ms | 888.89
| getChannelMembers | p99 | 25ms | 243ms | 218ms | 887.96
| getGroups | p99 | 10ms | 24ms | 14ms | 143.14
| getLicenseSelfServeStatus | p99 | 100ms | 242ms | 142ms | 142.18
| getUsers | p99 | 168ms | 395ms | 227ms | 135.39
| getPostsForChannelAroundLastUnread | p99 | 386ms | 801ms | 415ms | 107.61
| logout | p99 | 246ms | 481ms | 235ms | 95.64
| getFilteredUsersStats | p99 | 50ms | 96ms | 46ms | 92.46
| getRolesByNames | p99 | 49ms | 93ms | 44ms | 89.79
| updateCategoriesForTeamForUser | p99 | 920ms | 1.69s | 770ms | 83.70
| autocompleteChannelsForTeamForSearch | p99 | 2.576s | 4.587s | 2.011s | 78.07
| unfollowThreadByUser | p99 | 415ms | 585ms | 170ms | 40.96
| getUser | p99 | 140ms | 160ms | 20ms | 14.32
| saveReaction | p99 | 393ms | 426ms | 33ms | 8.40
| getClientConfig | p99 | 188ms | 203ms | 15ms | 7.97
| getPreferences | p99 | 80ms | 86ms | 6ms | 7.47
| getTeamsForUser | p99 | 71ms | 76ms | 5ms | 7.09
| addChannelMember | p99 | 1.851s | 1.972s | 121ms | 6.54
| getTeamsUnreadForUser | p99 | 145ms | 154ms | 9ms | 6.20
| createPost | p99 | 4.28s | 4.529s | 249ms | 5.82
| getChannelMember | p99 | 197ms | 205ms | 8ms | 4.07
| searchPostsInTeam | p99 | 2.364s | 2.456s | 92ms | 3.89
| getFilePreview | p99 | 287ms | 298ms | 11ms | 3.84
| createGroupChannel | p99 | 2.397s | 2.482s | 85ms | 3.55
| getAllTeams | p99 | 86ms | 89ms | 3ms | 3.48
| removeUserCustomStatus | p99 | 934ms | 960ms | 26ms | 2.78
| addTeamMember | p99 | 4.703s | 4.831s | 128ms | 2.72
| getChannelMembersForTeamForUser | p99 | 90ms | 92ms | 2ms | 2.22
| getTeamMembersForUser | p99 | 91ms | 93ms | 2ms | 2.19
| login | p99 | 918ms | 938ms | 20ms | 2.18
| getChannelsForTeamForUser | p99 | 92ms | 94ms | 2ms | 2.16
| getPublicChannelsForTeam | p99 | 98ms | 100ms | 2ms | 2.04
| getPostThread | p99 | 365ms | 370ms | 5ms | 1.37
| uploadFileStream | p99 | 2.262s | 2.291s | 29ms | 1.28
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| patchPost | avg | 1.059s | 91ms | -968ms | -91.42
| createCategoryForTeamForUser | avg | 91ms | 49ms | -42ms | -46.32
| deletePost | avg | 122ms | 66ms | -56ms | -45.76
| searchGroupChannels | avg | 22ms | 12ms | -10ms | -44.48
| followThreadByUser | avg | 70ms | 40ms | -30ms | -43.01
| getFilteredUsersStats | avg | 49ms | 29ms | -20ms | -40.87
| getCategoriesForTeamForUser | avg | 48ms | 33ms | -15ms | -31.49
| createChannel | avg | 34ms | 29ms | -5ms | -14.66
| createDirectChannel | avg | 449ms | 400ms | -49ms | -10.92
| updateCategoriesForTeamForUser | avg | 203ms | 185ms | -18ms | -8.88
| getLicenseSelfServeStatus | avg | 74ms | 68ms | -6ms | -8.14
| updatePreferences | avg | 25ms | 23ms | -2ms | -7.85
| getProfileImage | avg | 104ms | 100ms | -4ms | -3.86
| addChannelMember | avg | 435ms | 423ms | -12ms | -2.76
| getPostsForChannel | avg | 96ms | 94ms | -2ms | -2.08
| updateReadStateThreadByUser | avg | 111ms | 109ms | -2ms | -1.80
| createPost | avg | 1.213s | 1.199s | -14ms | -1.15
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| createCategoryForTeamForUser | p99 | 246ms | 99ms | -147ms | -59.88
| updateUserCustomStatus | p99 | 1.105s | 969ms | -136ms | -12.31
| searchGroupChannels | p99 | 99ms | 88ms | -11ms | -11.07
| getChannel | p99 | 193ms | 175ms | -18ms | -9.34
| followThreadByUser | p99 | 246ms | 232ms | -14ms | -5.70
| getCategoriesForTeamForUser | p99 | 234ms | 222ms | -12ms | -5.13
| updatePreferences | p99 | 242ms | 230ms | -12ms | -4.95
| getChannelStats | p99 | 165ms | 157ms | -8ms | -4.86
| autocompleteUsers | p99 | 340ms | 324ms | -16ms | -4.71
| createDirectChannel | p99 | 2.182s | 2.083s | -99ms | -4.54
| updateReadStateThreadByUser | p99 | 523ms | 500ms | -23ms | -4.40
| createChannel | p99 | 97ms | 93ms | -4ms | -4.12
| getTeamMember | p99 | 85ms | 82ms | -3ms | -3.54
| getPostsForChannel | p99 | 866ms | 849ms | -17ms | -1.96
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 6ms| 7ms | 1ms | 15.631
| |  P99| 64ms| 68ms | 4ms | 6.250
| BotStore.Get |  Avg| 9ms| 11ms | 2ms | 21.423
| |  P99| 90ms| 48ms | -42ms | -46.667
| BotStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 46ms| 49ms | 3ms | 6.490
| ChannelStore.Autocomplete |  Avg| 61ms| 62ms | 1ms | 1.632
| |  P99| 242ms| 241ms | -1ms | -0.413
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 86ms| 181ms | 95ms | 110.296
| |  P99| 2.576s| 4.587s | 2.011s | 78.066
| ChannelStore.CreateDirectChannel |  Avg| 62ms| 59ms | -3ms | -4.806
| |  P99| 493ms| 387ms | -106ms | -21.488
| ChannelStore.CreateInitialSidebarCategories |  Avg| 53ms| 33ms | -20ms | -37.497
| |  P99| 322ms| 322ms | 0s | 0.000
| ChannelStore.CreateSidebarCategory |  Avg| 79ms| 33ms | -46ms | -58.578
| |  P99| 246ms| 50ms | -196ms | -79.837
| ChannelStore.Get |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 86ms| 86ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersForUser |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 46ms| 46ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 43ms| 44ms | 1ms | 2.347
| |  P99| 242ms| 245ms | 3ms | 1.241
| ChannelStore.GetByName |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 81ms| 82ms | 1ms | 1.230
| ChannelStore.GetChannelUnread |  Avg| 10ms| 11ms | 1ms | 9.903
| |  P99| 90ms| 90ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 88ms| 90ms | 2ms | 2.270
| ChannelStore.GetChannelsByUser |  Avg| 11ms| 10ms | -1ms | -9.283
| |  P99| 88ms| 87ms | -1ms | -1.134
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 81ms| 82ms | 1ms | 1.227
| ChannelStore.GetFileCount |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 78ms| 85ms | 7ms | 8.944
| ChannelStore.GetGuestCount |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 82ms| 84ms | 2ms | 2.438
| ChannelStore.GetMember |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 49ms| 47ms | -2ms | -4.109
| ChannelStore.GetMemberCount |  Avg| 34ms| 33ms | -1ms | -2.982
| |  P99| 178ms| 185ms | 7ms | 3.924
| ChannelStore.GetMemberForPost |  Avg| 13ms| 12ms | -1ms | -7.865
| |  P99| 86ms| 86ms | 0s | 0.000
| ChannelStore.GetMembers |  Avg| 204ms| 207ms | 3ms | 1.468
| |  P99| 900ms| 898ms | -2ms | -0.222
| ChannelStore.GetMembersForUser |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 87ms| 89ms | 2ms | 2.304
| ChannelStore.GetMembersForUserWithPagination |  Avg| 27ms| 21ms | -6ms | -22.492
| |  P99| 50ms| 76ms | 26ms | 52.393
| ChannelStore.GetPinnedPostCount |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 84ms| 85ms | 1ms | 1.195
| ChannelStore.GetPublicChannelsForTeam |  Avg| 29ms| 30ms | 1ms | 3.394
| |  P99| 97ms| 100ms | 3ms | 3.080
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 47ms| 32ms | -15ms | -31.731
| |  P99| 233ms| 220ms | -13ms | -5.586
| ChannelStore.GetSidebarCategory |  Avg| 31ms| 21ms | -10ms | -31.799
| |  P99| 218ms| 106ms | -112ms | -51.376
| ChannelStore.GetTeamChannels |  Avg| 34ms| 29ms | -5ms | -14.723
| |  P99| 97ms| 93ms | -4ms | -4.124
| ChannelStore.IncrementMentionCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 69ms| 72ms | 3ms | 4.328
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 37ms| 34ms | -3ms | -8.152
| |  P99| 238ms| 343ms | 105ms | 44.096
| ChannelStore.SaveMember |  Avg| 53ms| 55ms | 2ms | 3.772
| |  P99| 348ms| 395ms | 47ms | 13.487
| ChannelStore.SearchGroupChannels |  Avg| 22ms| 12ms | -10ms | -44.753
| |  P99| 99ms| 88ms | -11ms | -11.110
| ChannelStore.UpdateLastViewedAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 74ms| 75ms | 1ms | 1.344
| ChannelStore.UpdateSidebarCategories |  Avg| 128ms| 134ms | 6ms | 4.673
| |  P99| 473ms| 863ms | 390ms | 82.394
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 5ms| 4ms | -1ms | -20.867
| |  P99| 68ms| 55ms | -13ms | -19.252
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 10ms| 8ms | -2ms | -20.278
| |  P99| 93ms| 89ms | -4ms | -4.304
| CommandWebhookStore.Cleanup |  Avg| 6ms| 26ms | 20ms | 322.049
| |  P99| 25ms| 50ms | 25ms | 101.214
| FileInfoStore.AttachToPost |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 97ms| 111ms | 14ms | 14.408
| FileInfoStore.Get |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 88ms| 88ms | 0s | 0.000
| FileInfoStore.GetForPost |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 77ms| 84ms | 7ms | 9.091
| FileInfoStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 91ms| 91ms | 0s | 0.000
| FileInfoStore.SetContent |  Avg| 17ms| 18ms | 1ms | 6.004
| |  P99| 173ms| 192ms | 19ms | 10.972
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 50ms| 49ms | -1ms | -2.008
| GroupStore.GetByName |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 60ms| 70ms | 10ms | 16.676
| GroupStore.GetGroups |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 65ms| 71ms | 6ms | 9.213
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 3ms| 10ms | 7ms | 263.884
| |  P99| 5ms| 49ms | 44ms | 888.889
| JobStore.Get |  Avg| 7ms| 13ms | 6ms | 84.450
| |  P99| 74ms| 92ms | 18ms | 24.168
| JobStore.GetAllByStatus |  Avg| 10ms| 11ms | 1ms | 10.333
| |  P99| 90ms| 94ms | 4ms | 4.447
| JobStore.GetCountByStatusAndType |  Avg| 11ms| 15ms | 4ms | 37.936
| |  P99| 169ms| 102ms | -67ms | -39.645
| JobStore.GetNewestJobByStatusesAndType |  Avg| 10ms| 12ms | 2ms | 19.248
| |  P99| 169ms| 131ms | -38ms | -22.485
| JobStore.Save |  Avg| 15ms| 8ms | -7ms | -46.087
| |  P99| 368ms| 85ms | -283ms | -77.007
| JobStore.UpdateOptimistically |  Avg| 5ms| 10ms | 5ms | 104.858
| |  P99| 37ms| 89ms | 52ms | 139.639
| JobStore.UpdateStatus |  Avg| 5ms| 7ms | 2ms | 39.659
| |  P99| 44ms| 46ms | 2ms | 4.585
| JobStore.UpdateStatusOptimistically |  Avg| 5ms| 10ms | 5ms | 96.183
| |  P99| 37ms| 163ms | 126ms | 338.165
| LinkMetadataStore.Get |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 77ms| 75ms | -2ms | -2.593
| LinkMetadataStore.Save |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 78ms| 90ms | 12ms | 15.288
| PluginStore.Delete |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 44ms| 42ms | -2ms | -4.596
| PluginStore.Get |  Avg| 6ms| 9ms | 3ms | 47.199
| |  P99| 24ms| 48ms | 24ms | 98.361
| PluginStore.List |  Avg| 4ms| 11ms | 7ms | 158.991
| |  P99| 39ms| 86ms | 47ms | 119.745
| PluginStore.SetWithOptions |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 87ms| 86ms | -1ms | -1.148
| PostAcknowledgementStore.GetForPost |  Avg| 11ms| 7ms | -4ms | -37.555
| |  P99| 98ms| 45ms | -53ms | -54.082
| PostAcknowledgementStore.GetForPosts |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 98ms| 98ms | 0s | 0.000
| PostPersistentNotificationStore.DeleteExpired |  Avg| 4ms| 3ms | -1ms | -26.783
| |  P99| 42ms| 22ms | -20ms | -47.344
| PostPersistentNotificationStore.Get |  Avg| 4ms| 6ms | 2ms | 56.513
| |  P99| 42ms| 48ms | 6ms | 14.199
| PostPersistentNotificationStore.GetSingle |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 57ms| 63ms | 6ms | 10.502
| PostPriorityStore.GetForPost |  Avg| 8ms| 7ms | -1ms | -12.194
| |  P99| 49ms| 47ms | -2ms | -4.059
| PostPriorityStore.GetForPosts |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 99ms| 99ms | 0s | 0.000
| PostStore.AnalyticsPostCount |  Avg| 526ms| 446ms | -80ms | -15.207
| |  P99| 995ms| 990ms | -5ms | -0.503
| PostStore.Delete |  Avg| 74ms| 31ms | -43ms | -58.274
| |  P99| 245ms| 229ms | -16ms | -6.544
| PostStore.Get |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 187ms| 186ms | -1ms | -0.534
| PostStore.GetEtag |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 89ms| 89ms | 0s | 0.000
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 49ms| 53ms | 4ms | 8.148
| PostStore.GetPostIdBeforeTime |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 74ms| 75ms | 1ms | 1.345
| PostStore.GetPostReminderMetadata |  Avg| 9ms| 10ms | 1ms | 11.312
| |  P99| 42ms| 45ms | 3ms | 7.100
| PostStore.GetPostReminders |  Avg| 20ms| 14ms | -6ms | -29.365
| |  P99| 220ms| 89ms | -131ms | -59.545
| PostStore.GetPosts |  Avg| 8ms| 9ms | 1ms | 12.399
| |  P99| 67ms| 80ms | 13ms | 19.372
| PostStore.GetPostsAfter |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 69ms| 87ms | 18ms | 26.115
| PostStore.GetPostsBefore |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 91ms| 91ms | 0s | 0.000
| PostStore.GetPostsByThread |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 80ms| 85ms | 5ms | 6.283
| PostStore.GetPostsSince |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 182ms| 185ms | 3ms | 1.647
| PostStore.GetSingle |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 73ms| 70ms | -3ms | -4.104
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 22ms| 23ms | 1ms | 4.636
| |  P99| 222ms| 229ms | 7ms | 3.160
| PostStore.SearchPostsForUser |  Avg| 188ms| 235ms | 47ms | 25.047
| |  P99| 2.348s| 2.372s | 24ms | 1.022
| PostStore.SetPostReminder |  Avg| 22ms| 27ms | 5ms | 22.241
| |  P99| 228ms| 239ms | 11ms | 4.835
| PostStore.Update |  Avg| 25ms| 24ms | -1ms | -4.038
| |  P99| 205ms| 149ms | -56ms | -27.316
| PreferenceStore.DeleteCategoryAndName |  Avg| 19ms| 8ms | -11ms | -58.448
| |  P99| 49ms| 47ms | -2ms | -4.056
| PreferenceStore.Get |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 88ms| 88ms | 0s | 0.000
| PreferenceStore.GetAll |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 76ms| 83ms | 7ms | 9.258
| PreferenceStore.Save |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 198ms| 197ms | -1ms | -0.504
| ProductNoticesStore.ClearOldNotices |  Avg| 38ms| 36ms | -2ms | -5.320
| |  P99| 50ms| 50ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 58ms| 58ms | 0s | 0.000
| |  P99| 470ms| 470ms | 0s | 0.000
| ReactionStore.GetForPost |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 79ms| 79ms | 0s | 0.000
| ReactionStore.Save |  Avg| 22ms| 24ms | 2ms | 9.150
| |  P99| 220ms| 229ms | 9ms | 4.087
| RoleStore.ChannelHigherScopedPermissions |  Avg| 8ms| 11ms | 3ms | 37.392
| |  P99| 46ms| 62ms | 16ms | 35.068
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 11ms| 13ms | 2ms | 18.110
| |  P99| 137ms| 157ms | 20ms | 14.633
| SessionStore.GetSessionsExpired |  Avg| 4ms| 9ms | 5ms | 120.497
| |  P99| 24ms| 96ms | 72ms | 300.617
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 68ms| 64ms | -4ms | -5.898
| SessionStore.Remove |  Avg| 4ms| 6ms | 2ms | 50.936
| |  P99| 22ms| 46ms | 24ms | 109.094
| SessionStore.Save |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 94ms| 96ms | 2ms | 2.125
| SessionStore.UpdateLastActivityAt |  Avg| 7ms| 8ms | 1ms | 13.447
| |  P99| 67ms| 70ms | 3ms | 4.504
| StatusStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 51ms| 62ms | 11ms | 21.384
| StatusStore.GetByIds |  Avg| 11ms| 10ms | -1ms | -9.089
| |  P99| 94ms| 95ms | 1ms | 1.065
| StatusStore.SaveOrUpdate |  Avg| 94ms| 96ms | 2ms | 2.124
| |  P99| 945ms| 982ms | 37ms | 3.915
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 5ms| 16ms | 11ms | 210.995
| |  P99| 45ms| 94ms | 49ms | 108.889
| StatusStore.UpdateLastActivityAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 72ms| 69ms | -3ms | -4.186
| SystemStore.GetByName |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 54ms| 60ms | 6ms | 11.160
| TeamStore.AnalyticsTeamCount |  Avg| 4ms| 8ms | 4ms | 95.496
| |  P99| 5ms| 48ms | 43ms | 868.201
| TeamStore.Get |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 68ms| 66ms | -2ms | -2.933
| TeamStore.GetAllPage |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 72ms| 75ms | 3ms | 4.173
| TeamStore.GetByName |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 70ms| 78ms | 8ms | 11.453
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 74ms| 77ms | 3ms | 4.060
| TeamStore.GetMember |  Avg| 3ms| 2ms | -1ms | -34.060
| |  P99| 40ms| 27ms | -13ms | -32.492
| TeamStore.GetTeamsByUserId |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 69ms| 75ms | 6ms | 8.670
| TeamStore.GetTeamsForUser |  Avg| 7ms| 8ms | 1ms | 13.791
| |  P99| 73ms| 78ms | 5ms | 6.816
| TeamStore.SaveMember |  Avg| 38ms| 38ms | 0s | 0.000
| |  P99| 225ms| 226ms | 1ms | 0.445
| ThreadStore.Get |  Avg| 8ms| 10ms | 2ms | 24.763
| |  P99| 80ms| 177ms | 97ms | 120.878
| ThreadStore.GetMembershipForUser |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 76ms| 78ms | 2ms | 2.644
| ThreadStore.GetTeamsUnreadForUser |  Avg| 10ms| 11ms | 1ms | 9.571
| |  P99| 92ms| 93ms | 1ms | 1.092
| ThreadStore.GetThreadFollowers |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 69ms| 68ms | -1ms | -1.455
| ThreadStore.GetThreadForUser |  Avg| 15ms| 16ms | 1ms | 6.480
| |  P99| 129ms| 130ms | 1ms | 0.776
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 88ms| 89ms | 1ms | 1.141
| ThreadStore.GetThreadsForUser |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 93ms| 92ms | -1ms | -1.080
| ThreadStore.GetTotalThreads |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 76ms| 78ms | 2ms | 2.633
| ThreadStore.GetTotalUnreadMentions |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 75ms| 78ms | 3ms | 3.993
| ThreadStore.GetTotalUnreadThreads |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 76ms| 76ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 77ms| 80ms | 3ms | 3.917
| ThreadStore.MaintainMembership |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 167ms| 172ms | 5ms | 2.988
| ThreadStore.MarkAllAsReadByChannels |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 81ms| 83ms | 2ms | 2.474
| ThreadStore.MarkAsRead |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 62ms| 62ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 62ms| 63ms | 1ms | 1.624
| TokenStore.Cleanup |  Avg| 8ms| 17ms | 9ms | 107.540
| |  P99| 25ms| 50ms | 25ms | 101.215
| UserAccessTokenStore.GetByToken |  Avg| 10ms| 6ms | -4ms | -41.263
| |  P99| 90ms| 45ms | -45ms | -49.999
| UserStore.AutocompleteUsersInChannel |  Avg| 76ms| 78ms | 2ms | 2.619
| |  P99| 373ms| 370ms | -3ms | -0.804
| UserStore.Count |  Avg| 24ms| 30ms | 6ms | 24.920
| |  P99| 49ms| 167ms | 118ms | 238.901
| UserStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 70ms| 69ms | -1ms | -1.438
| UserStore.GetAllProfiles |  Avg| 6ms| 7ms | 1ms | 15.454
| |  P99| 47ms| 48ms | 1ms | 2.139
| UserStore.GetAllProfilesInChannel |  Avg| 407ms| 418ms | 11ms | 2.700
| |  P99| 1.997s| 2.059s | 62ms | 3.104
| UserStore.GetByUsername |  Avg| 9ms| 12ms | 3ms | 32.023
| |  P99| 86ms| 137ms | 51ms | 59.016
| UserStore.GetForLogin |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 66ms| 70ms | 4ms | 6.089
| UserStore.GetMany |  Avg| 9ms| 5ms | -4ms | -46.137
| |  P99| 86ms| 41ms | -45ms | -52.323
| UserStore.GetProfileByIds |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 88ms| 88ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 89ms| 89ms | 0s | 0.000
| UserStore.GetProfilesInChannel |  Avg| 266ms| 254ms | -12ms | -4.518
| |  P99| 895ms| 692ms | -203ms | -22.676
| UserStore.GetUnreadCount |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 77ms| 77ms | 0s | 0.000
| UserStore.IsEmpty |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 30ms| 34ms | 4ms | 13.485
| UserStore.Save |  Avg| 81ms| 82ms | 1ms | 1.231
| |  P99| 247ms| 249ms | 2ms | 0.809
| UserStore.Search |  Avg| 32ms| 32ms | 0s | 0.000
| |  P99| 221ms| 222ms | 1ms | 0.452
| UserStore.Update |  Avg| 18ms| 19ms | 1ms | 5.648
| |  P99| 183ms| 205ms | 22ms | 12.007
| UserStore.UpdateFailedPasswordAttempts |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 67ms| 71ms | 4ms | 5.943
| UserStore.UpdateUpdateAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 47ms| 49ms | 2ms | 4.221
| UserTermsOfServiceStore.GetByUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 60ms| 70ms | 10ms | 16.664
| WebhookStore.GetOutgoingByTeam |  Avg| 12ms| 13ms | 1ms | 8.011
| |  P99| 93ms| 92ms | -1ms | -1.080
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 435ms| 423ms | -12ms | -2.761
| | P99| 1.851s| 1.972s | 121ms | 6.537
| addTeamMember | Avg| 1.224s| 1.231s | 7ms | 0.572
| | P99| 4.703s| 4.831s | 128ms | 2.721
| autocompleteChannelsForTeamForSearch | Avg| 86ms| 181ms | 95ms | 110.211
| | P99| 2.576s| 4.587s | 2.011s | 78.066
| autocompleteUsers | Avg| 64ms| 64ms | 0s | 0.000
| | P99| 340ms| 324ms | -16ms | -4.707
| createCategoryForTeamForUser | Avg| 91ms| 49ms | -42ms | -46.317
| | P99| 246ms| 99ms | -147ms | -59.877
| createChannel | Avg| 34ms| 29ms | -5ms | -14.663
| | P99| 97ms| 93ms | -4ms | -4.124
| createDirectChannel | Avg| 449ms| 400ms | -49ms | -10.915
| | P99| 2.182s| 2.083s | -99ms | -4.538
| createGroupChannel | Avg| 638ms| 708ms | 70ms | 10.965
| | P99| 2.397s| 2.482s | 85ms | 3.546
| createPost | Avg| 1.213s| 1.199s | -14ms | -1.154
| | P99| 4.28s| 4.529s | 249ms | 5.817
| createUser | Avg| 133ms| 134ms | 1ms | 0.754
| | P99| 494ms| 493ms | -1ms | -0.202
| deletePost | Avg| 122ms| 66ms | -56ms | -45.764
| | P99| 486ms| 483ms | -3ms | -0.617
| followThreadByUser | Avg| 70ms| 40ms | -30ms | -43.011
| | P99| 246ms| 232ms | -14ms | -5.703
| getAllTeams | Avg| 8ms| 8ms | 0s | 0.000
| | P99| 86ms| 89ms | 3ms | 3.483
| getCategoriesForTeamForUser | Avg| 48ms| 33ms | -15ms | -31.491
| | P99| 234ms| 222ms | -12ms | -5.132
| getChannel | Avg| 19ms| 18ms | -1ms | -5.361
| | P99| 193ms| 175ms | -18ms | -9.341
| getChannelMember | Avg| 17ms| 18ms | 1ms | 5.782
| | P99| 197ms| 205ms | 8ms | 4.069
| getChannelMembers | Avg| 11ms| 30ms | 19ms | 172.174
| | P99| 25ms| 243ms | 218ms | 887.964
| getChannelMembersForTeamForUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 90ms| 92ms | 2ms | 2.218
| getChannelMembersForUser | Avg| 23ms| 22ms | -1ms | -4.278
| | P99| 49ms| 49ms | 0s | 0.000
| getChannelStats | Avg| 11ms| 10ms | -1ms | -8.997
| | P99| 165ms| 157ms | -8ms | -4.861
| getChannelUnread | Avg| 12ms| 13ms | 1ms | 8.272
| | P99| 99ms| 99ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 10ms| 11ms | 1ms | 9.566
| | P99| 92ms| 94ms | 2ms | 2.162
| getChannelsForUser | Avg| 11ms| 11ms | 0s | 0.000
| | P99| 91ms| 92ms | 1ms | 1.100
| getClientConfig | Avg| 13ms| 14ms | 1ms | 7.811
| | P99| 188ms| 203ms | 15ms | 7.973
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getFilePreview | Avg| 71ms| 71ms | 0s | 0.000
| | P99| 287ms| 298ms | 11ms | 3.836
| getFileThumbnail | Avg| 58ms| 58ms | 0s | 0.000
| | P99| 245ms| 246ms | 1ms | 0.407
| getFilteredUsersStats | Avg| 49ms| 29ms | -20ms | -40.866
| | P99| 50ms| 96ms | 46ms | 92.462
| getGroups | Avg| 3ms| 5ms | 2ms | 58.375
| | P99| 10ms| 24ms | 14ms | 143.143
| getGroupsAssociatedToChannelsByTeam | Avg| 3ms| 11ms | 8ms | 295.539
| | P99| 5ms| 49ms | 44ms | 888.889
| getLicenseSelfServeStatus | Avg| 74ms| 68ms | -6ms | -8.140
| | P99| 100ms| 242ms | 142ms | 142.176
| getPostThread | Avg| 51ms| 50ms | -1ms | -1.942
| | P99| 365ms| 370ms | 5ms | 1.369
| getPostsForChannel | Avg| 96ms| 94ms | -2ms | -2.084
| | P99| 866ms| 849ms | -17ms | -1.963
| getPostsForChannelAroundLastUnread | Avg| 46ms| 64ms | 18ms | 39.432
| | P99| 386ms| 801ms | 415ms | 107.614
| getPreferences | Avg| 8ms| 9ms | 1ms | 12.297
| | P99| 80ms| 86ms | 6ms | 7.469
| getProfileImage | Avg| 104ms| 100ms | -4ms | -3.861
| | P99| 489ms| 488ms | -1ms | -0.205
| getPublicChannelsForTeam | Avg| 31ms| 32ms | 1ms | 3.212
| | P99| 98ms| 100ms | 2ms | 2.044
| getRolesByNames | Avg| 8ms| 10ms | 2ms | 25.364
| | P99| 49ms| 93ms | 44ms | 89.789
| getTeamMember | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 85ms| 82ms | -3ms | -3.539
| getTeamMembersForUser | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 91ms| 93ms | 2ms | 2.191
| getTeamsForUser | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 71ms| 76ms | 5ms | 7.086
| getTeamsUnreadForUser | Avg| 13ms| 14ms | 1ms | 7.481
| | P99| 145ms| 154ms | 9ms | 6.196
| getThreadsForUser | Avg| 13ms| 13ms | 0s | 0.000
| | P99| 96ms| 96ms | 0s | 0.000
| getUser | Avg| 10ms| 11ms | 1ms | 10.300
| | P99| 140ms| 160ms | 20ms | 14.324
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 17ms| 16ms | -1ms | -6.041
| getUsers | Avg| 12ms| 25ms | 13ms | 108.969
| | P99| 168ms| 395ms | 227ms | 135.391
| getUsersByIds | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 34ms| 33ms | -1ms | -2.934
| getUsersByNames | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 91ms| 90ms | -1ms | -1.103
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 133ms| 148ms | 15ms | 11.269
| | P99| 918ms| 938ms | 20ms | 2.179
| logout | Avg| 101ms| 149ms | 48ms | 47.499
| | P99| 246ms| 481ms | 235ms | 95.640
| patchPost | Avg| 1.059s| 91ms | -968ms | -91.421
| | P99| 494ms| 490ms | -4ms | -0.810
| removeUserCustomStatus | Avg| 227ms| 288ms | 61ms | 26.899
| | P99| 934ms| 960ms | 26ms | 2.783
| root | Avg| 0s| 14ms | 14ms | 9862.065
| | P99| 5ms| 235ms | 230ms | 4646.465
| saveReaction | Avg| 55ms| 58ms | 3ms | 5.481
| | P99| 393ms| 426ms | 33ms | 8.399
| searchAllChannels | Avg| 62ms| 62ms | 0s | 0.000
| | P99| 242ms| 242ms | 0s | 0.000
| searchGroupChannels | Avg| 22ms| 12ms | -10ms | -44.479
| | P99| 99ms| 88ms | -11ms | -11.075
| searchPostsInTeam | Avg| 210ms| 267ms | 57ms | 27.182
| | P99| 2.364s| 2.456s | 92ms | 3.891
| searchUsers | Avg| 34ms| 34ms | 0s | 0.000
| | P99| 225ms| 225ms | 0s | 0.000
| setPostReminder | Avg| 70ms| 72ms | 2ms | 2.858
| | P99| 244ms| 242ms | -2ms | -0.818
| unfollowThreadByUser | Avg| 43ms| 44ms | 1ms | 2.326
| | P99| 415ms| 585ms | 170ms | 40.963
| updateCategoriesForTeamForUser | Avg| 203ms| 185ms | -18ms | -8.876
| | P99| 920ms| 1.69s | 770ms | 83.695
| updatePreferences | Avg| 25ms| 23ms | -2ms | -7.851
| | P99| 242ms| 230ms | -12ms | -4.951
| updateReadStateThreadByUser | Avg| 111ms| 109ms | -2ms | -1.804
| | P99| 523ms| 500ms | -23ms | -4.400
| updateUserCustomStatus | Avg| 287ms| 332ms | 45ms | 15.699
| | P99| 1.105s| 969ms | -136ms | -12.312
| uploadFileStream | Avg| 515ms| 524ms | 9ms | 1.749
| | P99| 2.262s| 2.291s | 29ms | 1.282
| viewChannel | Avg| 32ms| 32ms | 0s | 0.000
| | P99| 243ms| 245ms | 2ms | 0.822
